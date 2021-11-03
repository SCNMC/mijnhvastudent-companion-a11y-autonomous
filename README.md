# Rapportage webtoegankelijkheid-test voor MijnHvA Companion

Datum webtoegankelijkheid-test: 25/10/2021

Webtoegankelijkheid-test uitgevoerd door: Shauri, Jean en Boudewijn

## 📚 Inhoudsopgave

- [Samenvatting](#samenvatting)
- [Achtergrond bij de evaluatie](#achtergrond-bij-de-evaluatie)
- [Afbakening](#afbakening)
- [Beoordelaars](#beoordelaars)
- [Beoordelingsproces](#beoordelingsproces)
- [Testresultaten en aanbevelingen](#testresultaten-en-aanbevelingen)
- [Referenties](#referenties)
- [Bijlagen](#bijlagen)
- [Licentie](#licentie)

## Samenvatting

Dit rapport beschrijft in hoeverre de website MijnHvA Compannion overeenstemt met de Web Content Accessibility Guidelines (WCAG) van het W3C. Na de achtergrondinformatie en afbakening van de test worden beoordelaars, beoordelingsproces en testresulltaten beschreven.

Conslusie van deze test luidt dat de MijnHvA Companion App bijna voldoet aan de WCAG 2.1 op niveau AAA, Behalve op de appearance, animation, controls en color contrast. Bij de appearance moet er nog goed gekeken worden naar de proximity bij de FAQ. Hier kan een een gebruiker met een minder visueel zicht de tekst hiervan minder of niet goed lezen. Niet al onze animation hebben de prefers/reduced/motion media query. Bij het tabben van de site kwamen we ook op 1 probleem uit, tijdens het tabben leest de screenreader de mobile nav voor terwijl die niet zichtbaar is. Verder was ons kleur contrast ook niet optimaal, ons witte achtergrond met de grijze tekst geeft geen goede contrast. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.



## Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 25/10/2021. De website kan ondertussen aangepast zijn.

## Afbakening

{Naam van de website}

{en doel van de website, wanneer relevant}

{Base URL van de website}

{Lijst met URLs die in de beoordeling meegenomen zijn}

{Als de website dynamisch is, screenshots van hetgeen beoordeeld is}

{Indicatie van pagina’s die handmatig beoordeeld zijn ten opzichte van semi-geautomatiseerde tools}

{URLs die niet beoordeeld zijn}

{Exacte datum, of reeks van data waarop beoordeling heeft plaatsgevonden}

{Natuurlijke taal/talen van de website}

## Beoordelaars

{Naam van de beoordelaar of het beoordelingsteam}

{Organisatie van de beoordelaars}

{Contactinformatie van de beoordelaar(s)}

{Expertisegebied van de beoordelaars op basis van naamgeving in de referentie: “Informatie over het gebruik van gecombineerde expertise voor het evalueren van webtoegankelijkheid”}

{Niveau van natuurlijke taal/talen waarin de beoordelaar(s) communiceert/communiceren}

## Beoordelingsproces

{Benoem het WCAG 2.1 niveau waarvoor de beoordeling is uitgevoerd, bv. WCAG 2.1 Niveau A, AA of AAA}

{Benoem de beoordelings- en evaluatietools en versies van de tools die gebruikt zijn}

{Beschrijf hoe handmatige beoordeling is uitgevoerd, bv. usability test of toegankelijkheidstest aan de hand van A11Y Project-checklist}

## ⚡ Testresultaten en aanbevelingen

{Samenvatting van testresultaten, bv. deze website {voldoet/ voldoet niet/ is dichtbij aan voldoen} aan de WCAG 2.1, op niveau A, AA of AAA.}

### 💪 Sterke punten

#### 👓 Screenreaders

Wij hebben de welkomspagina uitvoerig getest met screenreaders. Dit hebben wij gedaan door het apple voiceover programma te gebruiken. Dit programma hebben wij tijdens het testen aangezet en vervolgens onze ogen dicht gedaan. Het was ontzettend raar om zo over een pagina heen te gaan, maar het voiceover programma deed het verassend goed op onze website, hij haperde nergens en liep nergens vast.

#### 🎨 Kleurencontrast

Wij hebben bij de welkomspagina geprobeerd om een zo goed mogelijk kleurencontrast te creëren. Zo als in onderstaande foto te zien is is dit goed gelukt. Wij hebben met kleurconstrast de hoogst haalbare score behaald.

<img width="482" alt="Schermafbeelding 2021-11-02 om 14 58 28" src="https://user-images.githubusercontent.com/45170095/139861706-5f5b00a5-3320-4675-9987-fef8c9ad621c.png">

#### 🏠 Lighthouse

Wij hebben bij de welkomspagina twee keer een lighthouse toegankelijkheids test gedaan. Zie onderstaande foto's. Hier kwam de eerste keer een score van 76 uit. Wij hebben aan de hand van de commentaren van lighthouse de website aangepast, een voorbeeld hiervan was het toevoegen van `alt` tags op onze afbeeldingen. Vervolgens hadden wij een score van 100.

##### Eerste lighthouse check

<img width="1440" alt="Schermafbeelding 2021-10-27 om 12 18 08" src="https://user-images.githubusercontent.com/45170095/139865212-2e2e945b-626e-4a04-bf68-96f0182674be.png">


##### Tweede lighthouse check

<img width="1440" alt="Schermafbeelding 2021-10-27 om 15 14 34" src="https://user-images.githubusercontent.com/45170095/139865217-840db226-ec91-4542-8a84-f377c615b59c.png">

### Ontoegankelijke punten

De welkomspagina van MijnHvA Companion heeft een aantal ontoegankelijke punten, deze zijn als volgt: Het is niet mogelijk om op een goede manier over de pagina heen te navigeren met het gebruik van tab. Daarnaast is de lengte van de tekst soms te lang waardoor mensen met een verminderd zicht de teskt niet goed kunnen lezen.

### Checklist

##### Content

Use plain language and avoid figures of speech, idioms, and complicated metaphors

Onze welkomspagina gebruikt tekst op 8 grade reading level. Hierdoor is onze website begrijpelijk voor alle gebruikers en op deze manier word niemand uitgesloten die moeilijke begrippen of woorden niet begrijpt.

Make sure that button, a, and label element content is unique and descriptive

Button, a of label elementen die we hebben gebruikt voor onzen pagina hebben allemaal een unieke beschrijving. Hierdoor leest de screen reader wat er gebeurt wanneer een specifiek element zoals een button of a word geselecteerd.

Use left-aligned text for left-to-right (LTR) languages, and right-aligned text for right-to-left (RTL) languages.

All onze tekst op de website staat van links naar rechts. Onze website is hierdoor gemakkelijk te lezen.


##### Global code

Tijdens het valideren van de HTML kwamen wij als groepje op een aantal HTML fouten. Zo hadden wij bijvoorbeeld geen alt-tags gebruikt op onze afbeeldingen, een onjuiste structuur bij lijsten en hadden wij onze HTML niet ingesteld op Nederlands. Gelukkig waren dit vrij kleinschalige problemen hebben wij deze opgelost. 

##### Keyboard

Bij het testen van de website bezoeken met alleen het gebruik van een toetsenbord ging het voor het grootste gedeelte perfect, het is namelijk voor het grootste gedeelte mogelijk om met de tab toets over de pagina te navigeren. Helaas is dit niet overal het geval, het is namelijk zo dat het mobiele menu wordt meegenomen tijdens het gebruik van de tab toets op de pagina, terwijl deze standaard niet wordt getoond. Tot slot hebben wij geen focus state kunnen zetten op interactieve elementen.

##### Keyboard oplossingen

> Het tab probleem is op te lossen door het mobiele menu op display: none te zetten, maar dan is er een ander losstaand probleem m.b.t de animatie van het mobiele menu. 

> De focus state is op te lossen door op de desbetreffende elementen de `:focus` methode in CSS te gebruiken.

##### Images

Tijdens het testen van de afbeeldingen op de website kwamen wij er achter dat onze afbeeldingen geen alt tag hadden, deze hebben wij vervolgens toegevoegd. Hierna hebben wij met een screenreader getest of onze alt-tags goed waren en dit was in onze optiek het geval. Voor de rest waren onze afbeeldingen goed volgens de checklist.

##### Images oplossingen

> `Alt` tags gebruiken op de afbeeldingen. Zodat deze ook worden voorgelezen door screenreaders.

##### Headings

Bij het testen van de website hebben wij uiteraard ook gekeken naar de headings op de website. Onze gebruikte headings voldeden aan bijna alle punten van de checklist. Wij hadden namelijk perongeluk heading niveaus overgeslagen en hier ook geen logische volgorde in de heading niveaus gebruiken, wij gingen bijvoorbeeld van een h2 naar een h4 zonder een h3 te gebruiken.

##### Headings oplossingen

> Gebruik een logische volgorde in de heading levels: `h1, h2, h3`, enzovoort.

##### Lists

Use list elements (ol, ul, and dl elements) for list content

Op de list categorie hebben wij een probleem gevonden in onze code. Na het runnen van een lighthouse check kwam eruit dat in onze ul een div was gebruikt. Door dit probleem kregen wij eerst een lighthouse score van 76 procent. 

##### List oplossingen

> `:focus` Door alle div te veranderen naar li gaf lighthouse na het checken dit probleem niet meer aan.

##### Controls

Bij het testen van de controls vanaf de checklist ging eigenlijk ook alles goed in de test, alleen hadden de interactieve elementen geen :focus state. Daarnaast heeft de website ook geen skiplink om direct door te kunnen gaan naar belangrijke informatie op de website.

##### Controls oplossingen

> `:focus` state toevoegen op interactieve elementen.

> Skiplink toevoegen, zodat er direct naar belangrijke informatie op de website kan worden gegaan met de tab toets.

##### Tables

Use the table element to describe tabular data.

Task: Use the th element for table headers (with appropriate scope attributes).
Use the th element for table headers (with appropriate scope attributes).

Task: Use the caption element to provide a title for the table.
Use the caption element to provide a title for the table.

Opmerking

> `:focus` We hebbben voor onze website geen tables gebruikt dus dit is niet van toepassing.

##### Forms

##### Media

Bij het testen van de media op de website ging alles eigenlijk zoals gehoopt, alles werkte naar behoren en de media die wij hadden geplaatst kwam goed overeen met de punten  die op de checklist werden genoemd als referentiepunt.

##### Video

Bij het testen van video was het een iets ander verhaal, volgens de checklist is het namelijk gewenst om ondertiteling toe te voegen, maar dit was in ons geval niet nodig, omdat de video die wij gebruikt hebben voor het overgrote gedeelte al bestaat uit tekst op beeld.

##### Audio

Zoals bij video was dit voor ons niet nodig, omdat de video die wij hebben gebruikt al voor het overgrote gedeelte bestaat uit tekst op beeld.

##### Appearance

Volgens de checklist was de appereance van de website ook goed, alleen hadden wij een probleem bij het uitvoeren van de `straw` test. Hier kwamen wij er namelijk achter dat de tekst van de veelgestelde vragen te lang was voor mensen die zoom software gebruiken.

##### Appearance oplossingen

> Veelgestelde vragen korter maken d.m.v `word-wrap` in css. Hierdoor kunnen mensen met zoom software de tekst ook goed kunnen lezen en de vragen op een goede manier kunnen bekijken.

##### Animation

Onze website maakt niet echt gebruik van animaties, los van wat simpele transitions, maar deze zijn afgestemd aan de hand van de checklist.

##### Color contrast

Bij het testen van het kleurencontrast, was het contrast van de kleuren die wij op de website hebben gebruikt goed, alleen de tekst met een 'normale' grootte is één tint te grijs, deze moet iets meer een zwarte tint hebben, dan is het kleuren contrast van de website helemaal perfect op AAA niveau. 


##### Color contrast oplossingen

> De tekst met een 'normale' grootte, van kleur veranderen met de volgende css property: `color: #363636`. Hiermee wordt de color contrast score van AAA behaald. 

##### Mobile and touch

Bij het testen op een mobiel apparaat, was het even spannend om te kijken of de website het ook goed deed op een andere scherm oriëntatie, maar dit ging eigenlijk super goed. Voor de rest was onze website goed op mobiel volgens de checklist. Alleen werd door de checklist wel aangegeven dat op mobiel horizontaal scrollen niet gewenst is. 

##### Mobile and touch oplossingen

> E.v.t horizontaal scrollen weghalen van de instructies `section`. Dit kan door de `display: grid` weg te halen en de width van de `article` breder te maken.

{Neem links op naar de WCAG 2.1 succescriteria en technieken voor de ontoegankelijke punten}

{Voeg per check specifieke rapportage(s), of links naar rapportage(s) toe in de Wiki, bv. screenshots van tests}

{Schrijf per check aanbevelingen voor het verbeteren van ontoegankelijke punten}

{Beschrijf of verwijs per check naar een programma voor het monitoren van webstite toegankelijkheid, her-beoordeling aan de hand van beoordelingsinstrumenten etc.}

### Resultaten Usability test

Tot onze grote spijt was het bezoek aan het usability lab voor ons geen toegevoegde waarde. Dit komt doordat het usability lab draait op verouderde browsers. Onze website is met bepaalde 'nieuwe' css properties gemaakt, zoals `grid`, hierdoor was het niet mogelijk om onze website in het usability lab te testen, omdat onze website door de gebruikte browser dan volledig uitelkaar werd getrokken.

## Referenties

Referenties welke gebruikt zijn bij de webtoegankelijkheid-test. Deze referenties zijn allen in het Engels:

- [Overzicht en introductie van de Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/intro/wcag)
- [De complete Web Content Accessibility Guidelines 2.1 (WCAG)](https://www.w3.org/TR/WCAG21/)
- [Technieken voor WCAG 2.1](https://www.w3.org/WAI/WCAG21/Techniques/)
- [Bronnen voor beoordeling van webtoegankelijkheidsevaluatie ](http://www.w3.org/WAI/eval/)
- [Tools lijst voor semi-geautomatiseerde beoordeling van webtoegankelijkheid](https://www.w3.org/WAI/ER/tools/)
- [Informatie over het gebruik van gecombineerde expertise voor het evalueren van webtoegankelijkheid](https://www.w3.org/WAI/eval/reviewteams)
- [A11Y Project Checklist](https://www.a11yproject.com/checklist/)

{Vul aan waar nodig, haal weg wat niet relevant is}

## Bijlagen

{Geef een opsomming van de bijlagen, zoals links naar rapportages, screenshots en uitleg in de Wiki}

[Einde van het template]

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
