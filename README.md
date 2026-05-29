# drzewostan-io

Strona internetowa projektu **Drzewostan** — profesjonalnej, w pełni darmowej aplikacji dla leśników na Android i Desktop (bez reklam, bez ukrytych opłat).

- Aplikacja mobilna: [Google Play](https://play.google.com/store/apps/details?id=com.anioncode.drzewostan)
- Aplikacja (repozytorium): [github.com/Lukieoo/Drzewostan](https://github.com/Lukieoo/Drzewostan)
- Autor: [Paweł Krzyściak](https://lukieoo.github.io/pawel-krzysciak/)

---

## O projekcie

Drzewostan to aplikacja wspierająca codzienną pracę leśnika w terenie. Umożliwia przeprowadzanie profesjonalnych szacunków brakarskich, przeglądanie interaktywnej mapy leśnej z nakładką LMN oraz generowanie raportów PDF — wszystko bez potrzeby dostępu do internetu.

Zbudowana w technologii **Kotlin Multiplatform (KMP)**, działa natywnie na Androidzie i systemach desktopowych (Windows, macOS, Linux) ze wspólną bazą kodu.

---

## Funkcje aplikacji

### Szacunki brakarskie
- Rejestracja pierśnic i wysokości drzew z podziałem na gatunki
- Klasyfikacja jakości drewna (WA–WD) i sortymentacja
- Konfigurowalny skok grubości i zakres pierśnic
- Automatyczne przeliczenia miąższości metodą pierśnicową
- Generowanie raportu PDF (format A4) z pełnymi tabelami gatunkowymi
- Udostępnianie raportów e-mailem i komunikatorami bezpośrednio z urządzenia

### Interaktywna mapa leśna
- OpenStreetMap z nakładką WMS Leśnej Mapy Numerycznej (Bank Danych o Lasach)
- Śledzenie pozycji GPS w czasie rzeczywistym
- Niestandardowe markery: drzewa, mrowiska, pomniki przyrody
- Przypinanie szacunków do konkretnych lokalizacji na mapie

### Analiza wizualna
- Wykres kołowy struktury gatunkowej drzewostanu
- Wykresy miąższości i liczby drzew według gatunków
- Rozkład klas grubości dla każdego gatunku
- Podgląd sortymentów i klas jakości

---

## Strona internetowa

Niniejsze repozytorium zawiera stronę landingową aplikacji — zbudowaną z czystego **HTML + CSS**, bez zewnętrznych frameworków JavaScript.

```
drzewostan-io/
├── index.html           # Strona główna
├── privacy-policy.html  # Polityka prywatności
├── style.css            # Wszystkie style
└── assets/              # Screenshoty i ikona aplikacji
```

### Uruchomienie lokalne

Strona nie wymaga żadnego buildu — wystarczy otworzyć `index.html` w przeglądarce lub uruchomić dowolny serwer HTTP:

```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .
```

---

## Platformy

| Platforma | Status | Wymagania |
|-----------|--------|-----------|
| Android | Dostępna na Google Play | Android 11+ |
| Desktop (Windows / macOS / Linux) | Wkrótce | — |

---

## Licencja i kontakt

Projekt tworzony przez Pawła Krzyściaka.  
Kontakt: [pawkrzysciak@gmail.com](mailto:pawkrzysciak@gmail.com)  
Strona autora: [lukieoo.github.io/pawel-krzysciak](https://lukieoo.github.io/pawel-krzysciak/)
