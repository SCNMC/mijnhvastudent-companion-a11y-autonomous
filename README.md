> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Rapportage webtoegankelijkheid-test voor {naam van de website}

_Dit document is een template voor een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschilelnde tests kunnen worden vergeleken._

Datum webtoegankelijkheid-test: {datum}

Webtoegankelijkheid-test uitgevoerd door: {naamt}

## Inhoudsopgave

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

Dit rapport beschrijft in hoeverre de website {naam van de website} overeenstemt met de _Web Content Accessibility Guidelines (WCAG)_ van het W3C. Na de achtergrondinformatie en afbakening van de test worden beoordelaars, beoordelingsproces en testresulltaten beschreven.

Conslusie van deze test luidt dat de {Frontend Design & Development} website {niet voldoet/ voldoet/ dichtbij voldoen is aan} de WCAG 2.1, op niveau {A/ AA/ AAA}. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.

## Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op {datum}. De website kan ondertussen aangepast zijn.

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

## Testresultaten en aanbevelingen

{Samenvatting van testresultaten, bv. deze website {voldoet/ voldoet niet/ is dichtbij aan voldoen} aan de WCAG 2.1, op niveau A, AA of AAA.}

### Sterke punten

De welkomspagina van MijnHvA Companion heeft een aantal sterke punten, deze zijn als volgt: De welkomspagina is goed leesbaar voor screenreaders, heeft een goed kleurencontrast, goede typografie en een goede HTML structuur.

### Ontoegankelijke punten

De welkomspagina van MijnHvA Companion heeft een aantal ontoegankelijke punten, deze zijn als volgt: Het is niet mogelijk om op een goede manier over de pagina heen te navigeren met het gebruik van tab. Daarnaast is de lengte van de tekst soms te lang waardoor mensen met een verminderd zicht de teskt niet goed kunnen lezen.

### Checklist

##### Content

##### Global code

Tijdens het valideren van de HTML kwamen wij als groepje op een aantal HTML fouten. Zo hadden wij bijvoorbeeld geen alt-tags gebruikt op onze afbeeldingen, een onjuiste structuur bij lijsten en hadden wij onze HTML niet ingesteld op Nederlands. Gelukkig waren dit vrij kleinschalige problemen hebben wij deze opgelost. 

##### Keyboard

Bij het testen van de website bezoeken met alleen het gebruik van een toetsenbord ging het voor het grootste gedeelte perfect, het is namelijk voor het grootste gedeelte mogelijk om met de tab toets over de pagina te navigeren. Helaas is dit niet overal het geval, het is namelijk zo dat het mobiele menu wordt meegenomen tijdens het gebruik van de tab toets op de pagina, terwijl deze standaard niet wordt getoond. Tot slot hebben wij geen focus state kunnen zetten op interactieve elementen.

##### Keyboard oplossingen

> Het tab probleem is op te lossen door het mobiele menu op display: none te zetten, maar dan is er een ander losstaand probleem m.b.t de animatie van het mobiele menu. 

> De focus state is op te lossen door op de desbetreffende elementen de `<:focus>` methode in CSS te gebruiken.

##### Images

Tijdens het testen van de afbeeldingen op de website kwamen wij er achter dat onze afbeeldingen geen alt tag hadden, deze hebben wij vervolgens toegevoegd. Hierna hebben wij met een screenreader getest of onze alt-tags goed waren en dit was in onze optiek het geval. Voor de rest waren onze afbeeldingen goed volgens de checklist.

#### Images oplossingen

> Alt tags gebruiken op de afbeeldingen. Zodat deze ook worden voorgelezen door screenreaders.

##### Headings

Bij het testen van de website hebben wij uiteraard ook gekeken naar de headings op de website. Onze gebruikte headings voldeden aan bijna alle punten van de checklist. Wij hadden namelijk perongeluk heading niveaus overgeslagen en hier ook geen logische volgorde in de heading niveaus gebruiken, wij gingen bijvoorbeeld van een h2 naar een h4 zonder een h3 te gebruiken.

#### Headings oplossingen

> Gebruik een logische volgorde in de heading levels: `<h1, h2, h3>`, enzovoort.

##### Lists

##### Controls



##### Tables

##### Forms

##### Media

##### Video

##### Audio

##### Appearance

##### Animation

##### Color contrast

##### Mobile and touch

{Schrijf per check wat er uit de test is gekomen}

{Neem links op naar de WCAG 2.1 succescriteria en technieken voor de ontoegankelijke punten}

{Voeg per check specifieke rapportage(s), of links naar rapportage(s) toe in de Wiki, bv. screenshots van tests}

{Schrijf per check aanbevelingen voor het verbeteren van ontoegankelijke punten}

{Beschrijf of verwijs per check naar een programma voor het monitoren van webstite toegankelijkheid, her-beoordeling aan de hand van beoordelingsinstrumenten etc.}

### Resultaten Usability test

{Beschrijf per pagina de bevindingen uit jouw usability test in het lab.}

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
