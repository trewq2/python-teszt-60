# Python alapok – 60 kérdéses tudáspróba

## A csomag
- `index.html`: a diákoknak szánt önálló weboldal; GitHub Pages-en is működik.
- `Code.gs`: a Google Táblázatba mentő, újraszámoló Apps Script. Külön Python-projektbe kerüljön.
- `TANARI_MEGOLDOKULCS.md`: mind a 60 kérdés, helyes válasz és magyarázat.
- `KERDESBANK.json`: szerkeszthető kérdésbank; az index.html a saját példányát tartalmazza.
- `TELEPITES.md`: a Google-összekapcsolás lépései.

## A felmérő
60 kérdés, 60 perc, 60 pont. Minden kérdésnél pontosan egy helyes válasz van.
Hat témakör, témakörönként 10 kérdés. A Python-kódok behúzása a feladat része.
A teszt kódértelmezést mér; a weboldal nem futtatja a Python-részleteket.

Kérdés- és válaszkeverés; nincs visszalépés; egyszeri átugrás után a kihagyott kérdések visszatérnek.
Végleges beadás megerősítéssel, automatikus beadás időlejáratkor. Teljes képernyő kérése és oldalelhagyási jelzések; a harmadik észlelés lezárja a tesztet, az előző OSZTV-változattal egyezően.
Az ilyen jelzés nem bizonyítja a csalást; lehet technikai vagy véletlen esemény is.
Újrapróbálkozásnál új sorrend és külön azonosító keletkezik. A már központilag mentett korábbi eredmény megmarad.

Az eredménykártyák szűrnek: helyes, hibás, megválaszolatlan, oldalelhagyások.
A kérdések, helyes válaszok és magyarázatok 5 percig láthatók, a kiosztás eredeti sorrendjében.
A névvel készülő PDF-eredménylap tartalmazza a százalékot és jegyet is. A böngésző nyomtatási ablakában válaszd a Mentés PDF-ként lehetőséget.
A PDF nem kerül automatikusan a Drive-ra; az eredmények és részletes válaszok kerülnek a tanári táblázatba, az OSZTV-mintának megfelelően.

## Értékelés
| Pont | Pontos százalékos sáv | Jegy |
|---|---|---|
| 0–29 | 0% ≤ eredmény < 50% | 1 – elégtelen |
| 30–35 | 50% ≤ eredmény < 60% | 2 – elégséges |
| 36–41 | 60% ≤ eredmény < 70% | 3 – közepes |
| 42–47 | 70% ≤ eredmény < 80% | 4 – jó |
| 48–60 | 80% ≤ eredmény ≤ 100% | 5 – jeles |

A százalék kijelzése két tizedesre kerekített; a jegy nem kerekített százalékból készül.
Hibás vagy üres válasz 0 pont, pontlevonás nincs.

## Google Táblázat
https://docs.google.com/spreadsheets/d/1jB6iNnezaljyYmmUFGCB5WJZp7PFbfHqqQk61l3x_AA/edit?usp=drivesdk

A tanári táblázat maradjon privát. A toplista csak a megadott beceneveket, pontot és időt közli.
A kezdőoldal tájékoztatja a tanulót a név, osztály, válaszok és vizsgaadatok mentéséről.
A beérkezést a weboldal külön lekérdezéssel ellenőrzi. Küldési hiba esetén a válaszok helyben megmaradnak, és a mentés újrapróbálható.

## A használat korlátai
A böngésző nem tud más programokat, telefonhasználatot vagy fejlesztői eszközöket megbízhatóan letiltani.
A statikus oldalon az azonnali javításhoz a megoldókulcs is jelen van; az 5 perces elrejtés nem hozzáférés-védelem.
A szerver az elküldött válaszokból számol pontot és jegyet; a válaszadás önállóságát, a személyazonosságot és a kliens idejét ez nem hitelesíti.
Számonkéréskor tanári felügyelet szükséges, a teljes képernyő és a jelzések csak kiegészítő eszközök.
