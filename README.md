# Zenderhopper

Online radio met een grote frequentieschaal. Luister gewoon naar één zender, of laat hem om de paar minuten willekeurig wisselen tussen de zenders die jij kiest.

**Openen:** https://luka-f.github.io/zenderhopper/

- **Radio of Shuffle:** in Radio kies je zelf een zender en blijft die spelen. In Shuffle wisselt hij tussen de zenders in Mijn lijst die in rotatie staan; je stelt zelf in na hoeveel minuten.
- **Nederland.FM of Alle zenders:** alle zenders van nederland.fm, of daarbovenop ook die van radio.nl, zoals de regionale omroepen.
- **Echte FM-frequenties:** de schaal toont wat je op jouw plek via FM ontvangt. Bij je eerste bezoek vraagt de site waar je luistert: gebruik je locatie of typ een woonplaats of postcode. Kies je niets, dan is Amsterdam de standaard en staat er een vraagteken achter MHz. Onder de zendernaam zie je via welke zendmast je luistert. Schuif voorbij 108 MHz en je komt bij de zenders die hier geen FM hebben en via internet spelen; helemaal links ga je terug naar FM.
- **Zenders kiezen:** tegels om zenders in Mijn lijst te zetten, plus zoeken in de open database van [radio-browser.info](https://www.radio-browser.info/) en een eigen stream-adres toevoegen.
- **Geluidskwaliteit:** per zender zijn alle streamvarianten getest (MP3 en AAC, hoog en laag). Met *Hoge kwaliteit* speelt de best klinkende, met *Data sparen* de lichtste. Werkt een stream niet, dan valt hij vanzelf terug op de volgende. Naast "LIVE" zie je welke stream speelt, bijvoorbeeld AAC 96.
- **Instellingen:** één knop op de radio met je locatie, de geluidskwaliteit en Nederland.FM / Alle zenders.
- **Volledig scherm** met een draaiknop, en een zwevende mini-speler.
- **Over deze site:** het vraagteken rechtsonder legt uit waar Zenderhopper voor is en hoe het technisch werkt.
- Je lijst en instellingen blijven in je eigen browser bewaard; met *Lijst exporteren* maak je een reservekopie.

Sneltoetsen: `spatie` afspelen/pauze, `N` volgende zender, `F` volledig scherm, `Esc` terug, `↑` `↓` volume.

Bronnen: zenderlijsten van nederland.fm en radio.nl, FM-zendmasten uit het Antenneregister van de RDI, plaatsen en postcodes via PDOK.

De site bestaat uit `index.html` en `zenders-data.js`, zonder server of account. Download je ze allebei naar dezelfde map en open je `index.html` lokaal, dan werken ook zenders die alleen een onbeveiligde http-stream hebben.
