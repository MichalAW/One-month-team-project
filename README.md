# WDP Projekt Zespołowy

Czterosobowa praca zespołowa pod nadzorem projekt menadżera i dwóch mentorów koordynujących

## Opis projektu

Projekt zakłada stworzenie wizualnej strony dostarczonej według wymagań designera

## Inicjacja projektu

Po sklonowaniu projektu, zainstaluj wymagane paczki komendą `npm install`.

Teraz możesz zacząć pracę, korzystając z przygotowanych zadania `npm run watch`.

Wszystkie potrzebne do pracy pliki źródłowe znajdują się w folderze `src/`.

Link strony --> https://michalaw.github.io/One-month-team-project/

## NPM Scripts

Dostępne są 3 główne skrypty przyspieszające pracę:

- `build`: na bazie plików z folderu `src` buduje project w folderze `dist`
- `watch`: odpala `browser-sync`, obserwuje zmiany w folderze `src` i przebudowuje projekt
- `code-quality`: skrypt dokonuje automatycznego formatowania plików w folderze `src/`
  zgodnie z przyjętą konwencją formatowania kodu i sprawdza błędy w JS.

## Git Hooks

Projekt korzysta z Git Hooks - możliwości uruchamiania skryptów w reakcji na wybrane zdarzenia programu Git.

Za każdym razem gdy wykonasz komendę `git commit` zostanie uruchomiony skrypt `code-quality`
dla plików, które zostały wybrane do za-commit'owania.

## Konwencje i dobre praktyki

Praca indywidualna z co tygodniowym code-review,
głównie przy dopisywaniu skryptów js, tworzeniu komponentów, oraz stylowaniu na scss

## Moje zadania z jira

1. Create section--promotion
2. Create section--features
3. Create section--products
