# Sejf Rodzinny

**Bezpieczny sejf na dane Twojej rodziny. Wszystko zostaje na Twoim telefonie.**

PESEL dziecka, numer dowodu, seria paszportu, numer polisy — dane, których potrzebujesz raz na
kwartał i nigdy nie pamiętasz, gdzie je zapisałeś. Sejf Rodzinny trzyma je w jednym miejscu,
zaszyfrowane, i nigdzie ich nie wysyła.

🔗 **Strona aplikacji:** https://codebite.github.io/sejfrodzinny/ ·
[English version](https://codebite.github.io/sejfrodzinny/en/)

## Bezpieczeństwo

- **AES-256-GCM** — szyfrowanie uwierzytelnione, wykrywa manipulację plikiem sejfu
- **PBKDF2**, 100 000+ iteracji, unikalna sól dla każdego sejfu
- **Zero-knowledge** — odszyfrowane dane istnieją tylko w RAM i są kasowane przy zablokowaniu aplikacji
- **Brak sieci** — bez kont, serwerów, analityki i reklam; aplikacja działa w pełni offline
- **Kopia zapasowa** — eksport/import zaszyfrowanego pliku `.sejf`

## Prywatność

Aplikacja nie zbiera i nie udostępnia żadnych danych.
Pełna treść: [Polityka prywatności](https://codebite.github.io/sejfrodzinny/privacy.html) (PL / EN).

## Status

W przygotowaniu do publikacji w Google Play (`com.roslan.sejfrodzinny`).

## Kontakt

radoslaw.roslan@gmail.com

## Co jest w tym repozytorium

Wyłącznie **publiczna strona aplikacji** (landing PL/EN + polityka prywatności), serwowana przez
GitHub Pages z gałęzi `main`. Repozytorium jest publiczne tylko dlatego, że Pages z prywatnego
repo wymaga płatnego planu. **Kod źródłowy aplikacji jest prywatny.**

Strukturę strony rozwijamy w repo aplikacji (`docs/site/`) i stamtąd kopiujemy tutaj.

## Licencja

© 2026 Radosław Rosłan. Zawartość tego repozytorium — teksty, grafiki, zrzuty ekranu i polityka
prywatności — jest chroniona prawem autorskim. **Wszelkie prawa zastrzeżone**; publiczna widoczność
repozytorium nie oznacza zgody na ponowne wykorzystanie tych materiałów.
