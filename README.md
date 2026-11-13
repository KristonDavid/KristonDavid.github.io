# Tetőfedés és bádogozás

## A projekt célja

A projekt célja egy valós vállalkozás weboldalát utánzó, reszponzív, egyoldalas bemutatkozó oldal elkészítése. Az oldal egy tetőfedéssel és bádogozással foglalkozó vállalkozást mutat be, és segít a lehetséges megrendelőknek áttekinteni a szolgáltatásokat, a szakmai hátteret, az alkalmazott technológiákat és a tájékoztató munkadíjakat.

## Célközönség

Az oldal elsődleges célközönsége azok a magánszemélyek, társasházak és szervezetek, akik tetőfedési, bádogozási, javítási vagy felújítási munkához keresnek szolgáltatót.

## Követelmények és célok

- Az oldal magyar nyelven, áttekinthetően mutassa be a vállalkozást és szolgáltatásait.
- A látogatók a navigációval gyorsan elérhessék az egyes tartalmi részeket.
- A tartalom asztali és mobil képernyőn is használható legyen.
- A weboldal HTML, CSS és Bootstrap használatával készüljön.
- A Git verziókövetés dokumentálja a fejlesztés főbb lépéseit.
- Az oldal és a felhasznált tartalmak ellenőrzése előzze meg a közzétételt.

## Tartalom és működés

Az oldal egyetlen lapból áll, az alábbi fő részekkel:

- Szolgáltatások: csatornák, szegélyek, tetőfedések és lágyfedések.
- Bemutatkozás: a vállalkozás tapasztalata és munkavégzési területe.
- Technológiák: a kivitelezés szakmai szempontjai, anyagai és garanciája.
- Munkadíjak: tájékoztató árakat összefoglaló táblázat.

A navigációs menü az oldal megfelelő szakaszaira ugrik. A reszponzív elrendezéshez Bootstrap 5.3.3 készült; a Bootstrap JavaScript-csomagja a navigáció összecsukható, mobilnézetű működését szolgálja. Az oldal jelenlegi változata nem tartalmaz saját JavaScript-funkciót vagy szerveroldali szolgáltatást.

## Technológiák

- HTML5 a szemantikus tartalomszerkezethez.
- CSS a megjelenés kialakításához.
- Bootstrap 5.3.3 a rácsrendszerhez, reszponzív elrendezéshez és navigációhoz.
- Git a forráskód változásainak követéséhez.

## Fájlok

- [index.html](index.html): az oldal tartalma és szerkezete.
- [style.css](style.css): az egyedi stílusok.
- [forras/forras.txt](forras/forras.txt): a felhasznált szöveges alapanyag és a kiinduló referenciák.
- [forras/images](forras/images): a weboldalhoz használt képfájlok.

## Források és tervezési alap

A szöveges alapanyag a `forras/forras.txt` fájlban található. Az ott megadott kiinduló webes referenciák: [tetofedomester.hu](https://tetofedomester.hu/), [tetore-fel.hu](https://tetore-fel.hu/) és [tetorefel.hu](https://tetorefel.hu/). Ezeket tájékozódási alapként használtam a tartalom témájához és felépítéséhez.

A képek a `forras/images/` mappában vannak. A közzététel előtt a képek pontos eredeti forrását és felhasználási engedélyét ellenőrizni, majd szükség esetén a dokumentációban feltüntetni kell.

## Fejlesztési folyamat

1. Téma és célközönség meghatározása.
2. Tartalmi alapanyag és képek összegyűjtése, az oldal felépítésének megtervezése.
3. Az oldal elkészítése HTML, CSS és Bootstrap használatával.
4. Megjelenés és működés ellenőrzése különböző képernyőméreteken.
5. Hibák javítása, majd a kész oldal közzététele.

## Ellenőrzési szempontok

Közzététel előtt ellenőrizendő, hogy:

- minden navigációs hivatkozás a megfelelő szakaszra mutat;
- a képek betöltődnek, és értelmes alternatív szöveggel rendelkeznek;
- a táblázat és a szövegek mobilnézetben is olvashatók;
- nincs vízszintes görgetést okozó vagy egymást fedő tartalom;
- a HTML-szerkezet és a hivatkozások validálhatók;
- a felhasznált szövegek és képek forrása, illetve felhasználási feltételei tisztázottak.

## Lehetséges továbbfejlesztések

- Kapcsolati szakasz hozzáadása tényleges, ellenőrzött elérhetőségekkel.
- Egyedi arculat és részletesebb látványterv kialakítása.
- A hiányzó vagy hibás képalternatívák pótlása, valamint a navigáció és szakaszazonosítók ellenőrzése.
- A JavaScript-követelmény tisztázása a feladat kiírása alapján, és szükség esetén egy kis, indokolt interaktív funkció megvalósítása.
