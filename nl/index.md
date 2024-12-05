---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS.html
translation-title: Nederlandse vertaling van de Standaard voor Publieke Code
---

# Leidraad voor open source werken in publieke organisaties

De Standaard voor Publieke Code is een set criteria die publieke organisaties ondersteunt bij het samen ontwikkelen en onderhouden van software en bijbehorend beleid.

De Standaard voor Publieke Code is een leidraad voor publieke organisaties die willen samenwerken aan open source-oplossingen met soortgelijke organisaties elders. Het bevat adviezen voor beleidsmakers, managers, ontwikkelaars en ontwerpers. De Standaard voor Publieke Code ondersteunt bij het gezamenlijk ontwikkelen van codebases die open, herbruikbaar, leesbaar, te verantwoorden, toegankelijk en duurzaam zijn. De standaard is toepasbaar op codebases van publieke organisaties op alle niveaus - van supranationaal tot gemeentelijk.

De Standaard voor Publieke Code beschrijft '[publieke code](glossary.html#publieke-code)' als open source software ontwikkeld door publieke organisaties, samen met het beleid en de richtlijnen die nodig zijn voor samenwerking en hergebruik.

De criteria van de Standaard voor Publieke Code zijn afgestemd op richtlijnen en _best practices_ in open source software-ontwikkeling.

Aanvullende context en achtergrondinformatie zijn te vinden in het [voorwoord](foreword).

## Inhoudsopgave

* [Auteurs](AUTHORS)
* [Voorwoord bij de vertaling](translation-foreword)
* [Voorwoord](foreword)
* [Leeswijzer](readers-guide)
* [Begrippenlijst](glossary)
* [Criteria](criteria/){% assign sorted = site.pages | sort:"order" %}{% for page in sorted %}{% if page.dir == "/nl/criteria/" %}{% if page.name != "index.md" %}{% if page.title %}
  * [{{page.title}}]({{site.baseurl}}{{page.url}}){% endif%}{% endif%}{% endif%}{% endfor %}
* [Bijdragen](CONTRIBUTING)
* [Gedragscode](CODE_OF_CONDUCT)
* [Governance](GOVERNANCE)
* [Versiegeschiedenis](CHANGELOG)
* [Licentie](LICENSE)
