# Kamień Pomorski, dz. 100/15 – model 3D koncepcji

Interaktywna przeglądarka 3D koncepcji zagospodarowania działek 100/15, 100/16, 100/19 (obręb 0003 Kamień Pomorski) z kontekstem w promieniu 500 m.

- obrót / przesuw / zoom, gotowe widoki (lotniczy, plan, od północy, z wjazdu)
- karty budynków (kondygnacje, pow. zabudowy, PUC, rzędne)
- palety kolorów: Akcent, Typy budynków, Makieta, Naturalna, Oryginał
- tryb zrzutu do wizualizacji AI: kadry 16:9/3:2/4:3/1:1/9:16, światło, eksport PNG do 3840 px, kopiowanie obrazu i promptu
- budynki typu A (A1–A4, B) na postumencie 1,5 m z garażem podziemnym i rampą zjazdową
- łącznice dróg koncepcji z ul. Lipową i Kanałową
- drzewa otoczenia (`models/trees.json`), łodzie i żaglówki na Zalewie, krowy na łąkach
- bilans terenu, warstwy
- symulacja nasłonecznienia dla 21.03, 21.06, 21.12

Strona jest statyczna (three.js z CDN), modele w `models/` to GLB skompresowane meshopt.

## Uruchomienie lokalne

```bash
python -m http.server 8000
```

i otwórz http://localhost:8000.

## Źródła danych

GUGiK (ULDK, NMT/NMPT 1 m, ortofoto), BDOT10k, © OpenStreetMap contributors (ODbL).
Układ PL-2000 strefa 5 (EPSG:2176), wysokości PL-EVRF2007-NH.
