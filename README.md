# Berkenweg – 3D

Interactief 3D-model (WebGL) van de Berkenweg: de woningen 9, 9a, 9c en 9d en het landschap eromheen.
Alles zit in één bestand: `index.html` (geometrie, materialen, landschapsdata en de muziek van de rondleiding).
Openen in een browser met hardwareversnelling.

## Parameters

Zet een parameter achter het adres, bijvoorbeeld `index.html?verkennen`. Meerdere combineren met `&`, bijvoorbeeld `index.html?verkennen&kerst`.

| Parameter | Wat het doet | Opmerking |
|---|---|---|
| *(geen)* | Rondleiding (kioskweergave): opbouw, rondleiding en rondvlucht over de omgeving, samen 2:30 met muziek. | Standaard. Huisknop linksboven gaat naar `?verkennen`. |
| `?verkennen` | Het volledige model met alle bediening: zelf rondkijken, binnen lopen, datum/tijd en zonnestand in de bovenbalk. | |
| `?rondleiding` | Zelfde als zonder parameter. | Blijft werken voor oude links. |
| `?record` | Rondleiding die zichzelf opneemt als mp4 met muziek (2:30); het bestand wordt aan het eind opgeslagen. | Mag de browser geen geluid zonder klik afspelen, dan één klik op de rode opnameknop. Bediening is tijdens de opname uitgeschakeld. |
| `?winter` | Winter met sneeuw. | |
| `?kerst` | Kerstversiering. | Zet ook winter aan. |
| `?schemer` | Schemer. | In de rondleiding het vaste schemerlicht; bij `?verkennen` de tijd op een half uur na zonsondergang. |
| `?zonderomgeving` | Landschap rondom uit. | In de rondleiding komt het dan ook niet bij 0:21 erbij. |
| `?zonderkompas` | Kompas uit. | |

## Bronnen

- Landschap: PDOK open data (AHN4, BGT, BAG, BRK), CC BY 4.0.
- Muziek rondleiding: Motivational Corporate Post Rock by Infraction, music from #InAudio (https://inaudio.org/).

## Wijzigingen

### 2026-10-28
- VR ook vanaf de rondleiding-pagina (de standaardpagina): knop "Bekijk in VR" onder de afspeelknop en een VR-knop in de knoppenrij links, alleen zichtbaar in een browser met VR.
- VR (eerste versie, bv. Meta Quest): knop "VR" in de bovenbalk van `?verkennen`, alleen zichtbaar in een browser met VR. Alleen 9c (zonder landschap en buren) op ware grootte; rondkijken met het hoofd, linker stick lopen (door muren heen), rechter stick draaien in stappen, A/X verdieping omhoog, B/Y omlaag.

### 2026-10-22
- Bedienen > Woning: schakelaar "Eettafels wisselen" verwisselt de eethoek van de woonkamer en die van de serre (tafel met stoelen).

### 2026-10-13
- Standaard opent nu de rondleiding; het volledige model via `?verkennen`. De huisknop in de rondleiding gaat naar `?verkennen`.
- Nieuwe link-optie `?record`: rondleiding die zichzelf opneemt (mp4 met muziek), met afsluitende vlucht over de dierenweide.
- Donkere modus: achtergrond antraciet in plaats van bijna zwart, letters en kopjes lichter (beter leesbaar). De kleine kaart rechtsonder houdt zijn eigen kleuren in een donker kader.
- Titel linksboven en paginatitel (ook in de rondleiding): "Berkenweg". Onder Tonen heet "Buren" nu "Nummers", met ook Nr. 9c (standaard aan) om 9c te verbergen.
- Rondleiding-link: het landschap staat eerst uit en komt bij 0:21 (als 9a staat, net voordat de camera omzwenkt) met een plof erbij.
- Donkere modus voor de pagina (schuifje zon/maan in de bovenbalk); volgt standaard de systeeminstelling.
- Witte vlakjes op de hoeken van de woning (kopgevels en lange gevels) weg: daar is het nu gewoon baksteen.
- Vlindertuin: grassprieten steken niet meer door de gevel van de woonkamer, de serre en de aanbouw.

### 2026-10-12
- Datum en tijd in de bovenbalk: zon en maan staan op de juiste plek voor Doornspijk (Nederlandse tijd, zomertijd), met meelopende schaduwen, schemer, nacht met sterren en maan, en zonsopkomst/-ondergang. Standaard de huidige tijd; de knop Schemer zet de tijd op een half uur na zonsondergang. De rondleiding-link houdt het vaste licht.
- Laadtijd bijna gehalveerd: muziek pas laden bij afspelen, kerstversiering pas opbouwen bij Kerst, sneller rekenwerk, ongebruikte data verwijderd.
- Video-opname neemt nu ook de muziek van de rondleiding op.
- Kompas (aan/uit via Tonen, kioskknop of `?zonderkompas`), noordrichting gecontroleerd met kadaster en BAG.
- Bloembakken 9c op de echte maten (voordeur 2 × 6 blokken, slaapkamer 1 4 blokken) en regenpijp op de gevel van slaapkamer 1.

### 2026-10-08
- Zonnepanelen op alle woningen gelijk aan die van 9c (1,215 × 1,75 m); dakkapel 9a in het midden.
- Vlindertuin langs de oostgevel.
- Landschap rondom (bos, wal, zandverstuiving De Haere), dierenweide met kerstversie, rondvlucht over de omgeving.
