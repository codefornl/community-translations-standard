---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS.html
translation-title: Nederlandse vertaling van de Standaard voor Publieke Code
order: 3
description: Codebases die door meerdere partijen worden ontwikkeld en gebruikt, hebben meer kans op een langlevende community.
---

# Maak de codebase herbruikbaar en overdraagbaar

Het maken van herbruikbare en overdraagbare [code](../glossary.html#code) stelt beleidsmakers, ontwikkelaars en ontwerpers in staat om wat is ontwikkeld te hergebruiken, te testen, te verbeteren en die verbeteringen weer in te brengen, wat leidt tot betere kwaliteit, goedkoper onderhoud en hogere betrouwbaarheid.

Het doordacht en doelgericht ontwerpen van een [codebase](../glossary.html#codebase) voor herbruikbaarheid zorgt ervoor dat de missie, visie en scope van de codebase door meerdere partijen wordt gedeeld. Codebases die door meerdere partijen worden ontwikkeld en gebruikt, hebben meer kans op een langlevende community.

Door een codebase zo te organiseren dat deze is samengesteld uit goed gedocumenteerde modules, worden de herbruikbaarheid en het onderhoud ervan verbeterd. Een module is gemakkelijker te hergebruiken in [een andere context](../glossary.html#verschillende-contexten) als het doel ervan duidelijk gedocumenteerd is.

Broncode die niet afhankelijk is van de situatiespecifieke infrastructuur van een bijdrager, leverancier of implementatie kan door elke andere bijdrager worden getest.

## Vereisten

- De codebase MOET worden ontwikkeld om in verschillende contexten herbruikbaar te zijn.

- De codebase MOET voor uitvoering en begrip onafhankelijk zijn van geheime, niet openbaar gemaakte, bedrijfseigen of niet-open software of diensten onder licentie.

- De codebase ZOU door meerdere partijen MOETEN worden gebruikt.

- De roadmap ZOU MOETEN worden bepaald vanuit de behoeften van meerdere partijen.

- De ontwikkeling van de codebase ZOU een samenwerking MOETEN zijn tussen meerdere partijen.

- Om [broncode](../glossary.html#broncode) aan te passen aan contextspecifieke behoeften ZOU gebruik MOETEN worden gemaakt van configuratie.

- De codebase ZOU *localizable* MOETEN zijn, dat wil zeggen aanpasbaar aan locatiespecifieke omstandigheden zoals taal, karakterset en symbolen.

- De broncode en de bijbehorende documentatie MOGEN GEEN situatiespecifieke informatie bevatten.

- Codebase-modules ZOUDEN zodanig MOETEN zijn gedocumenteerd dat hergebruik in codebases in andere contexten mogelijk is.

- De software MAG GEEN diensten of platformen vereisen die slechts door één leverancier worden geleverd.

## Hoe te testen

- Vraag aan iemand in een vergelijkbare rol bij een andere organisatie of hij of zij de codebase zou willen gebruiken en wat daarvoor nodig is.

- Controleer of de codebase kan worden uitgevoerd zonder gebruik te maken van propriëtaire of niet-open software of services.

- Als de codebase zich nog in een vroeg stadium van ontwikkeling bevindt, vóórdat er een release is die gereed is voor productie, controleer dan of er aanwijzingen zijn dat er de ambitie is om samen te werken.

    - Of als de codebase erg volwassen en stabiel is en er zeer zelden oplossingen, patches of bijdragen zijn:

        - Controleer of de codebase wordt gebruikt door meerdere partijen of in meerdere contexten.

        - Controleer of er gedocumenteerde en gebudgetteerde samenwerkingsafspraken zijn.

    - Anders:

        - Controleer of de codebase wordt gebruikt door meerdere partijen of in meerdere contexten.

        - Controleer of er meerdere partijen bijdragen aan de codebase.

- Controleer of de codebase-bestanden en commit-geschiedenis geen situatiespecifieke gegevens bevatten.

- Controleer of de software kan worden geïmplementeerd en uitgevoerd zonder dat er diensten of platformen van één leverancier nodig zijn.

## Beleidsmakers in de publieke sector: wat je moet doen

- Documenteer je [beleid](../glossary.html#beleid) zo duidelijk en gedetailleerd dat het ook buiten de oorspronkelijke context kan worden begrepen.

- Zorg ervoor dat je organisatie als een bekende gebruiker in de codebase wordt vermeld.

- Identificeer andere organisaties waarmee je teams kunnen samenwerken.

## Managers: wat je moet doen

- Zorg ervoor dat belanghebbenden en proceseigenaren begrijpen dat herbruikbaarheid een expliciet doel van de codebase is. Dit vermindert de *technical debt* en zorgt voor duurzaamheid van de codebase.

- Zorg ervoor dat je teams samenwerken met andere teams.

## Ontwikkelaars en ontwerpers: wat je moet doen

De broncode moet worden ontworpen:

- voor hergebruik door andere gebruikers en organisaties, ongeacht hun locatiespecifieke omstandigheden,

- om een algemeen probleem op te lossen in plaats van een specifiek probleem,

- in logisch samenhangende en geïsoleerde modules,

- zodat iemand in een vergelijkbare organisatie met een vergelijkbaar probleem (delen van) de oplossing kan gebruiken.

Zorg ervoor dat de documentatie van de codebase de build- en runtime-afhankelijkheden beschrijft. Als je context vereist dat je implementeert op propriëtaire platformen of propriëtaire componenten gebruikt, zorg er dan voor dat anderen zonder deze componenten kunnen ontwikkelen, gebruiken, testen en implementeren.

Bij elke commit controleren beoordelaars of de inhoud geen situatiespecifieke gegevens bevat, zoals hostnamen, persoons- en organisatiegegevens of tokens en wachtwoorden.

## Meer informatie

* [Making source code open and reusable](https://www.gov.uk/service-manual/technology/making-source-code-open-and-reusable) door de UK Government Digital Service.

* [Localization vs. Internationalization](https://www.w3.org/International/questions/qa-i18n) door het World Wide Web Consortium.
