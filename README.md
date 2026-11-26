# NmG Oefenen

Een kleine web-app om NmG-gebaren te oefenen met je eigen woordenlijsten. Hij werkt op iPhone en iPad.

- Je maakt zoveel lijsten als je wilt en oefent met één of meer lijsten tegelijk.
- De woorden komen in willekeurige volgorde. Weet je een woord niet, dan komt het een paar kaarten later terug.
- Per woord houdt de app bij hoe vaak je het goed en fout had. Een woord staat op *Ken ik* als je het 3 keer achter elkaar wist.
- Alles blijft op je eigen apparaat. Er gaat niets naar een server. Met "Back-up maken" bewaar je je lijsten als bestand, bijvoorbeeld in iCloud Drive.

## Bestanden

- `index.html`: de hele app (opmaak en code).
- `sw.js`: zorgt dat de app ook zonder internet werkt.
- `manifest.webmanifest` en `icons/`: naam en icoon op het beginscherm.

## Online zetten met GitHub Pages

1. Open GitHub Desktop, kies **File > Add Local Repository** en selecteer deze map.
2. Klik op **Publish repository**. Zet het vinkje "Keep this code private" uit (GitHub Pages is gratis voor openbare repositories). Alleen de app-code wordt openbaar, je woordenlijsten niet.
3. Ga op github.com naar de repository, dan **Settings > Pages**. Kies bij *Branch* `main` en map `/ (root)` en klik op **Save**.
4. Na een minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/nmg-oefenen/`.

## Op de iPad of iPhone zetten

1. Open het adres in **Safari**.
2. Tik op het deel-icoon en kies **Zet op beginscherm**.
3. Gebruik de app voortaan via het icoon. Let op: de app op het beginscherm en dezelfde pagina in Safari hebben elk hun eigen opslag.

## Nieuwe versie

Pas de bestanden aan, commit en push. De app haalt bij de volgende start met internet zelf de nieuwe versie op. Je lijsten blijven gewoon staan.
