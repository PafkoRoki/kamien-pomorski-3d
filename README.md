# Kamień Pomorski, dz. 100/15 – model 3D koncepcji

Interaktywna przeglądarka 3D koncepcji zagospodarowania działek 100/15, 100/16, 100/19 (obręb 0003 Kamień Pomorski) z kontekstem w promieniu 500 m.

- obrót / przesuw / zoom, gotowe widoki (lotniczy, plan, od północy, z wjazdu)
- karty budynków (kondygnacje, pow. zabudowy, PUC, rzędne)
- bilans terenu, warstwy, tryb makiety
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
