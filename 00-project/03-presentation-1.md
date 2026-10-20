---
table-scale: 80%
---

# Személyre szabott futó- és kerékpárkörök optimalizált tervezése OpenStreetMap adatok alapján

Szerző: Fonyó Botond  
Neptun: B5J8X5  
Témavezető: Oláh Gábor  
Projektazonosító: 2026-OG-04

---
<!-- @slide Probléma -->

## Probléma
A jelenlegi útvonaltervezők többnyire A pontból B pontba érkező utakat generálnak. Azonban a legtöbb hobbi futónak/kerékpározónak gyakran a kiindulási pontra visszatérő körökre van szüksége. Az aktuális alkalmazásoknál ritkán lehet beállítani a kívánt távolságot és a sportolói preferenciákat, melyek kimondottan fontosak a tökéletes mozgáshoz.


---
<!--@slide Célfelhasználók-->

## Célfelhasználók
A webalkalmazás célközönségét elsősorban olyan amatőr sportolók alkotják akik:
- Ismeretlen környéken szeretnének edzeni  (nyaralás, utazás)
- A megszokott útvonalaik helyett új kihívásokat keresnek
- Specifikus edzésterv alapján dolgoznak (adott szintemelkedés/távolság)
- Rehabilitáció során stabil és egyenes útra van szükségük
  

---
<!--@slide Tervezett Hatókör-->

## Tervezett hatókör
| Kategória         | Funkció és leírás                                                                 |
| ----------------- | --------------------------------------------------------------------------------- |
| Paraméterezés     | Kezdőpont, távolság, útminőség, szintemelkedés és ezek súlyozásának megvadása     |
| Adatmodell        | OSM-alapú úthálózat feldolgozása, élek súlyozása, gráf alapú implementálás        |
| Útvonal generálás | Zárt körök tervezése két különböző algoritmussal, két különöző kimenttel          |
| Megjelenítés      | Térképes megjelenítés, és alapvető statisztikák biztosítása az alkalmazáson belül |
| Minőségbiztosítás | A legfontosabb algoritmusok automatizált tesztelése                               |


---
<!--@slide Nincs benne a hatókörben-->

## Nincs benne a hatókörben
- Időjárási adatok integrálása az adott helyen
- Népszerűség és jelenlegi forgalom figyelembe vétele
- Korábbi útvonalak mentése (lehetséges bővítés)
- Felhasználói fiók, többfelhasználós funkciók

---
<!--@slide Kezdeti felhasználói utak-->

## Kezdeti felhasználói utak
1) A felhasználó megadja a kiindulási pontot és beállítja a preferenciáit (távolság, tereptípus, max. meredekség)
2) A rendszer a háttérben az OSM adatokból felépített gráf alapján optimalizált, zárt útvonalakat számol
3) A sportoló megtekinti a térképen megjelenített legalább két útvonalat, és össszehasoníltja őket
4) Kiválasztja a számára tökéletes utat

---
<!--@slide Következő lépések-->

## Következő lépések
- OpenStreetMap adatok letöltése és feldolgozása
- Gráf alapú implementáció elméleti háttere
- Zárt körök generálására alkalmas algoritmusok vizsgálata és kiválasztása
- Webalkalmazás keretrendszerének felállítása

