---
name: Fonyó Botond
neptun: B5J8X5
id: 2026-OG-04
github: https://github.com/fonyobotond/project_b5j8x5 
trello: https://trello.com/b/fJXtNcjD/projectb5j8x5
---
# Személyre szabott futó- és kerékpárkörök optimalizált tervezése OpenStreetMap adatok alapján

## Célok

Egy verziókezelt útvonaltervező webalkalmazás fejlesztése, mely OpenStreetMap adatok alapján a felhasználó egyedi preferenciáihoz igazodó, a kiindulási pontra visszatérő futó- vagy kerékpárköröket generál. A preferenciák között lehet a távolság, szintemelkedés vagy akár a tereptípus is. A projekt végeredménye egy olyan alkalmazás lesz, ahol a térképes megjelenítés mellett alapvető statisztikai adatok is láthatóak lesznek.


## Hatókör

### Benne van a hatókörben

- Felhasználók által kiválasztott prioritások kezelése: kiindulási pont, kívánt távolság, út minősége, szintemelkedés
- OSM-alapú úthálózat gráfos implementációja
- Gráf éleinek súlyozása szintemelkedés valamint tereptípus alapján
- Zárt, kezdőpontra visszatérő útvonalak generálása
- Térképes megjelenítés, utólag a statisztika tárolása
- Legalább kettő különböző optimális útvonal generálása
- Több útvonal-generálási algoritmus használata
- Fontosabb algoritmusokhoz automatizált tesztek írása

### Nincs benne a hatókörben

- Időjárási adatok integrálása az adott helyen
- Népszerűség és a jelenlegi forgalom figyelembe vétele
- Korábbi felhasználói útvonalak mentése, tárolása, és ezek alapján történő tanulás.
- Felhasználói fiókok, hitelesítés és többfelhasználós funkciók


## Jegyzetek
A projekt kliens-szerver architektúrára épül, melyhez a megjelenítést, az API-kat és a backend motor nyelvét a 02-specification.md-ben pontosítom!