# Tomasz Mościcki — English Studio

Gotowa statyczna strona internetowa. Nie wymaga npm, instalowania zależności ani kompilacji.

## Publikacja przez GitHub Pages

1. Rozpakuj ZIP na komputerze.
2. Utwórz repozytorium na GitHub, np. `english-studio`.
3. Wgraj zawartość rozpakowanej paczki do głównego katalogu repozytorium: `index.html`, `refinements.css`, folder `assets` i pozostałe dołączone pliki. Nie wgrywaj samego ZIP-a ani dodatkowego katalogu nadrzędnego.
4. Zapisz pliki na gałęzi `main`.
5. W repozytorium otwórz **Settings → Pages**.
6. W **Build and deployment → Source** wybierz **Deploy from a branch**.
7. Wybierz gałąź **main** i folder **/(root)**, następnie **Save**.
8. Po zakończeniu publikacji adres strony znajdziesz w **Settings → Pages**.

Najprościej użyć publicznego repozytorium. Możliwość publikacji z prywatnego repozytorium zależy od planu GitHub.

Dokumentacja: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Zawartość

- `index.html` — treść strony, podstawowe style i obsługa okien z dokumentami.
- `refinements.css` — dodatkowe style i dostosowanie do telefonów.
- `assets/` — filmy, zdjęcia, dyplomy i referencje.
- `.nojekyll` — plik wyłączający przetwarzanie Jekyll.

## Podgląd i edycja

Otwórz `index.html` w przeglądarce. Opcjonalnie uruchom w katalogu strony `python -m http.server 8000` i wejdź na http://localhost:8000.

Teksty zmieniaj w `index.html`, wygląd w `refinements.css`. Zachowaj względne ścieżki do materiałów. Po zapisaniu zmian w repozytorium GitHub Pages ponownie opublikuje stronę.

## Stan eksportu

Eksport z 22.09.2026: telefon 451 687 466 i e-mail tomasz.moscicki.english@gmail.com u góry oraz w sekcji kontaktowej; moduł rezerwacji usunięty; oba dyplomy dostępne w podglądzie. Wszystkie materiały multimedialne są dołączone lokalnie.

Paczka jest niezależna od hostingu Sites. Nie zawiera jego konfiguracji, historii Git ani dawnego generatora strony. Nie dodano licencji zezwalającej na ponowne wykorzystanie materiałów przez osoby trzecie.
