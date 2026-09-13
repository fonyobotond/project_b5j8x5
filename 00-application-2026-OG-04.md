---
name: Fonyó Botond
neptun: B5J8X5
id: 2026-OG-04
---
# Személyre szabott futó- és kerékpárkörök optimalizált tervezése OpenStreetMap adatok alapján

## A brief értelmezése

A projektben egy útvonaltervező alkalmazás készítése a feladat, személyre szabott körútvonalak generálásával. Az alkalmazás emellett alapvető statisztikai adatokat is tárol, valamint a felhasználó adja meg az útvonalra vonatkozó preferenciákat. A rendszer a generálás közben a szintemelkedést, útburkolatot és a tereptípust is figyelembe veszi. A végső eredmény egy webalkalmazás lesz, ahol a térképes megjelenítés mellett alapvető statisztikai adatok is láthatóak lesznek.
## Miért én lennék alkalmas erre a projektre?

Aktív sportolóként a mindennapjaim szerves részét képzi a testmozgás. Biciklizésnél legtöbbször nehézséget okozott a megfelelő útvonal megtervezése, a nem biztonságos útviszonyok és a távolságok miatt. Érdekel ezeknek az alkalmazásoknak a mögöttes logikája valamint felépítése, aminek megértéséhez ez a projekt kiváló hátteret biztosítana. Szerintem ez az alkalmazás nagyszerű lenne mindennapi használatra azoknak, akik szeretnek statisztikát vezetni sportolásukról. Mindenképp külön motivációt jelentene az, hogy egy ilyen hasznos alkalmazás implementálását végezhetném.

## Releváns tapasztalat és előzmények

Egyetemi tanulmányaim során sok különböző programozási nyelvvel találkoztam, amikbe szívesen mélyebben beleásnám magam a projekt alatt. A webprogramozás mindig jobban érdekelt, mert hamarabb lehet látható eredményt elérni, és többet tudok kreatívkodni. Többször gyakoroltam már Pythonban különféle kisebb feladatokkal, amiket örömmel csináltam szabadidőmben. Mindenképpen csinálnék adatbázist is a projekthez, hogy a nyáron megszerzett szakmai gyakorlati tudásomat is kamatoztathassam.

## Tervezett megközelítés

Először meghatároznám a körútvonal-tervezés elméleti hátterét, az utak vizsgálandó paramétereit (szintemelkedés, burkolat, tereptípus) és a felhasználói preferenciák szabályrendszerét. Ezután az OpenStreetMap adatok feldolgozását végezném el Pythonban (OSMnx package), majd ezeket az adatokat egy relációs SQL adatbázisba importálnám be. Ezt követően implementálnám és összehasonlítanám az útvonalgeneráló algoritmusokat. Végül egy API-n keresztül összekötöm a webes felülettel, ahol a felhasználó egy interaktív térképen láthatja a megtervezett útvonalat és a hozzá tartozó statisztikákat. A webes frontend fejlesztésénél javascript-et használnék html-el és css-el összefűzve.

## Kezdeti terv

1. Elméleti háttér, valamint a szabályrendszer tisztázása
2. Az adatbázis felépítésének megtervezése, OpenStreetMap adatok szerkezetének kialakítása
3. Térképadatok letöltése, importálása SQL adatbázisba (Python), alap útvonalkeresés kipróbálása
4. Két különböző algoritmus lefejlesztése a körútvonalak generálására, majd ezek tesztelése és összehasonlítása
5. Webes kezelőfelület és az API elkészítése, majd a kettő összekötése
6. A kész webalkalmazás tesztelése valós helyszíneken és adatokon, illetve a generált útvonalak minőségének értékelése.

## További információ

A projekt előrehaladását az elejétől fogva a publikus GitHub repóban vezetem. Privát, érzékeny adatokat nem fogok megosztani.