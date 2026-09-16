# MixPalette

Mobilna aplikacja PWA do wyliczania przybliżonych mieszanek farb Vallejo i innych palet.

## Funkcje

- wybór koloru na interaktywnym kole lub przez kod HEX,
- receptura obliczana wyłącznie z posiadanych farb,
- proporcje w częściach i kroplach,
- kolekcja farb dodawanych kodem produktu,
- ręczna korekta proporcji,
- lokalna biblioteka zapisanych receptur,
- instalacja na ekranie głównym i działanie offline.

> Mieszanki są cyfrowym przybliżeniem. Pigment, krycie, podłoże i wyschnięcie farby mogą zmienić rzeczywisty rezultat.

## Uruchomienie lokalne

Pliki aplikacji znajdują się w katalogu `dist`. Wystarczy uruchomić w nim dowolny lokalny serwer HTTP, np.:

```bash
python3 -m http.server 8080 --directory dist
```

Następnie otwórz `http://localhost:8080`.

## Publikacja

Workflow GitHub Pages publikuje katalog `dist` automatycznie po zmianie gałęzi `main`. W ustawieniach repozytorium wybierz **Settings → Pages → Source: GitHub Actions**.

## Prywatność

Lista farb i receptury są zapisywane wyłącznie lokalnie w przeglądarce urządzenia (`localStorage`).

## Licencja

MIT
