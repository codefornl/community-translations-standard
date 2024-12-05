---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS.html
translation-title: Nederlandse vertaling van de Standaard voor Publieke Code
order: 2
description: Zo is het gemakkelijker om te begrijpen hoe de code werkt en waarom het is zoals het is.
---

# Bundel beleid en broncode

Toegang tot zowel de [broncode](../glossary.html#broncode) als het [beleid](../glossary.html#beleid) biedt de bouwstenen waarmee iedereen de codebase kan implementeren in hun lokale context of kan bijdragen aan de verdere ontwikkeling van de [codebase](../glossary.html#codebase).

Inzicht in het domein en het beleid binnen dat domein is fundamenteel om te begrijpen welke problemen een codebase probeert op te lossen en en op welke manier de codebase dat doet.

Om te kunnen evalueren of een codebase in een nieuwe context kan worden toegepast, moet een organisatie begrijpen welke proceswijzigingen daarvoor nodig zijn of hoe ze extra configureerbaarheid aan de bestaande oplossing kan toevoegen om deze aan de nieuwe context aan te passen.

## Vereisten

- De codebase MOET het beleid bevatten waarop de broncode is gebaseerd.

- Als beleid is gebaseerd op broncode, MOET die broncode in de codebase worden opgenomen, tenzij deze wordt gebruikt voor fraudedetectie.

- Beleid ZOU MOETEN worden aangeleverd in machineleesbare en ondubbelzinnige formaten.

- [Continue integratietests](../glossary.html#continue-integratie) ZOUDEN MOETEN valideren dat de broncode en het beleid coherent worden uitgevoerd.

## Hoe te testen

- Controleer bij een ambtenaar of alle beleidsregels waarop de broncode is gebaseerd, zijn opgenomen.

- Controleer bij een ambtenaar of alle broncode waarop het beleid is gebaseerd, is opgenomen.

- Controleer of het beleid door een machine kan worden geïnterpreteerd.

- Controleer of de integratietests op coherente uitvoering van de broncode en het beleid slagen.

## Beleidsmakers in de publieke sector: wat je moet doen

- Werk samen met ontwikkelaars en ontwerpers om ervoor te zorgen dat er geen discrepantie is tussen de beleidscode en de broncode.

- Geef de relevante beleidsteksten op voor opname in de [repository](../glossary.html#repository). Als de tekst niet in het Engels beschikbaar is, geef dan ook een Engelse samenvatting. Zorg ervoor dat je de standaarden opneemt waaraan je organisatie zich wil houden en alle organisatieprocessen die van invloed zijn op de ontwikkelings- of implementatiecontext van de codebase voor je organisatie.

- Geef referenties en verwijzingen naar teksten die het beleid ondersteunen.

- Documenteer beleid in formaten die ondubbelzinnig en machineleesbaar zijn, zoals die gepubliceerd door de [Object Management Group](https://www.omg.org/spec/).

- Volg het beleid met [hetzelfde versiebeheer](maintain-version-control.html) en dezelfde documentatie die worden gebruikt om de broncode te volgen.

- Controleer regelmatig hoe de broncode in de codebase is gewijzigd en of deze nog steeds overeenkomt met de [bedoelingen van het beleid](document-codebase-objectives.html).

- Neem relevant beleid op dat van invloed is op de community, codebase en ontwikkeling, waaronder wettelijke verplichtingen zoals de [Algemene Verordening Gegevensbescherming](https://eur-lex.europa.eu/eli/reg/2016/679/oj) of de [EU-richtlijn webtoegankelijkheid](https://digital-strategy.ec.europa.eu/en/policies/web-accessibility), of mensenrechtenbeleid, zoals bijvoorbeeld een toezegging van een publieke organisatie zich in te zetten voor gelijke kansen.

## Managers: wat je moet doen

- Houd beleidsmakers, ontwikkelaars en ontwerpers betrokken en verbonden gedurende het hele ontwikkelingsproces.

- Zorg ervoor dat beleidsmakers, ontwikkelaars en ontwerpers dezelfde doelen nastreven.

## Ontwikkelaars en ontwerpers: wat je moet doen

- Raak vertrouwd met de procesmodelleringsnotatie die beleidsmakers in je organisatie gebruiken en leer deze te gebruiken.

- Werk samen met beleidsmakers om ervoor te zorgen dat er geen discrepantie is tussen de beleidscode en de broncode.

- Geef feedback over hoe beleidsdocumentatie duidelijker kan worden gemaakt.

## Meer informatie

* [Business Process Model and Notation](https://en.wikipedia.org/wiki/Business_Process_Model_and_Notation) op Wikipedia.

* [BPMN Quick Guide](https://www.bpmnquickguide.com/view-bpmn-quick-guide/) door Trisotech.

* [Decision Model and Notation](https://en.wikipedia.org/wiki/Decision_Model_and_Notation) op Wikipedia.

* [Case Management Model Notation](https://en.wikipedia.org/wiki/CMMN) op Wikipedia.
