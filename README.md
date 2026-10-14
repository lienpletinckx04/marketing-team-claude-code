# Ons Marketingteam in Claude Code

**8 afdelingen. 40 gespecialiseerde agents. Eén CEO.** Een compleet marketingteam dat je in Claude Code aanstuurt.

Elke agent is een Claude Code-subagent met een eigen rol, werkwijze en output. De Strateeg (CEO) maakt het plan, de specialisten voeren het uit.

## Wat je nodig hebt

- [Claude Code](https://claude.com/claude-code) geïnstalleerd (terminal, desktop-app of VS Code).
- Geen codeerkennis. Je typt gewoon in het Nederlands wat je wil.

## Installatie

1. Kloon of fork deze repo, of kopieer de map `.claude/` naar je eigen project.
2. Open de map in Claude Code.
3. Vul `marketing/merk.md`, `marketing/doelgroep.md` en `marketing/doelen.md` in.
4. Typ:

```
/marketing ik wil de komende drie maanden 30 leads per maand uit LinkedIn en SEO
```

De Strateeg maakt een plan, de hoofdsessie voert de agents uit en alles wordt opgeslagen in `marketing/`.

Je kan ook één agent rechtstreeks aanspreken:

```
Laat de copywriter een landingspagina schrijven voor mijn AI-audit.
```

## Wat je krijgt: een voorbeeldrun

In `voorbeelden/asklien/` staat een volledige run met AskLien.ai als case: ingevulde merkbasis, het plan van de Strateeg en drie echte outputs.

| Bestand | Van agent | Wat het is |
|---|---|---|
| [plan.md](voorbeelden/asklien/plan.md) | strateeg | Plan met 6 stappen voor 20 audit-aanvragen in Q4 |
| [landingspagina-ai-audit.md](voorbeelden/asklien/content/landingspagina-ai-audit.md) | copywriter | Volledige landingspagina, met gekozen kop en motivatie |
| [reel-ai-speeltje.md](voorbeelden/asklien/social/reel-ai-speeltje.md) | content-creator | Reel-script in twee kolommen: gesproken en in beeld |
| [welkomstflow.md](voorbeelden/asklien/email/welkomstflow.md) | email-copywriter | 5 mails over 7 dagen, met onderwerpregels en timing |

Zo zie je vóór je iets invult wat het team oplevert.

## Vijf agents gaan diep

De 40 agents hebben allemaal een duidelijke rol, werkwijze en output. Vijf agents hebben daarbovenop een uitgewerkte methode met frameworks, checklists en voorbeelden, omdat ze het verschil maken in het dagelijks werk:

- `strateeg`: zeven draaiboeken voor de meest voorkomende doelen, plus een vast planformaat.
- `copywriter`: tone-of-voice-regels, landingspaginastructuur in negen secties, drie koptypes, verboden woorden.
- `content-creator`: tien hooktypes, formats voor reels, carrousels en LinkedIn, checklist.
- `email-copywriter`: onderwerpregelregels, mailopbouw, welkomst-, verkoop- en reactivatieflow.
- `concurrentie-analist`: vaste vergelijkingstabel en een methode om de open positie te vinden.

Elke andere agent weet wat hij niet doet en verwijst door naar de juiste collega.

## Het team

### 👑 CEO

| Agent | Wat die doet |
|---|---|
| `strateeg` | Stuurt het hele marketingteam aan en zorgt dat jouw doelen bereikt worden. |

### 🟠 Onderzoek & Concurrentie

| Agent | Wat die doet |
|---|---|
| `marktonderzoeker` | Analyseert markt, doelgroep en trends. |
| `concurrentie-analist` | Analyseert concurrenten: aanbod, prijzen, positionering, kanalen en zwaktes. |
| `klantinzichten-specialist` | Haalt inzichten uit klantfeedback, reviews, interviews en supportvragen. |
| `doelgroep-analist` | Bouwt en verfijnt doelgroepsegmenten en persona's. |
| `markttrend-specialist` | Signaleert nieuwe kansen, trends en ontwikkelingen in de markt en technologie. |

### 🟡 Strategie & Merk

| Agent | Wat die doet |
|---|---|
| `merkstrateeg` | Ontwikkelt merkstrategie en positionering: missie, merkbelofte, waarden, merkpersoonlijkheid en tone of voice. |
| `merkverhaal-specialist` | Schrijft krachtige merkverhalen, oorsprongsverhalen en kernboodschappen. |
| `positionerings-specialist` | Bepaalt de unieke positie in de markt ten opzichte van concurrenten. |
| `propositie-specialist` | Ontwikkelt en verbetert de value proposition en het aanbod. |
| `campagne-strateeg` | Bedenkt campagnestrategie en overkoepelende creatieve concepten. |

### 🔵 SEO & Vindbaarheid

| Agent | Wat die doet |
|---|---|
| `technical-seo-specialist` | Zorgt dat de website technisch sterk is: crawlbaarheid, snelheid, structuur, indexering, structured data. |
| `keyword-specialist` | Onderzoekt en kiest de juiste zoekwoorden per pagina en onderwerp. |
| `on-page-seo-specialist` | Optimaliseert bestaande content en pagina's: titels, meta descriptions, koppen, interne links en leesbaarheid. |
| `linkbuilding-specialist` | Zorgt voor kwalitatieve backlinks via outreach, gastcontent, partnerschappen en digitale PR. |
| `lokale-seo-specialist` | Optimaliseert voor lokale vindbaarheid: Google Bedrijfsprofiel, lokale pagina's, reviews en vermeldingen. |

### 🟢 Content & Copy

| Agent | Wat die doet |
|---|---|
| `content-strateeg` | Ontwikkelt de contentstrategie: thema's, pijlers, formats, kanalen en funnelrol per content. |
| `copywriter` | Schrijft overtuigende teksten voor web, landingspagina's en campagnes. |
| `blog-specialist` | Schrijft en optimaliseert blogs en artikelen die ranken én gelezen worden. |
| `beeldontwerper` | Creëert visuals, infographics en banners als HTML/SVG of als gedetailleerde beeldbriefing. |
| `content-planner` | Plant en beheert de contentkalender: wat, wanneer, waar en door wie. |

### 🟣 Social Media

| Agent | Wat die doet |
|---|---|
| `social-media-strateeg` | Ontwikkelt de social media strategie: kanaalkeuze, doelen, contentmix en ritme. |
| `community-manager` | Beheert en betrekt de community: reacties, DM's, gesprekken en moderatie. |
| `content-creator` | Maakt social media content: posts, carrousels, reel-scripts en captions. |
| `trend-analist` | Signaleert trends, formats en kansen op social media. |
| `influencer-manager` | Identificeert en werkt samen met influencers en partners. |

### 🩷 Leads & Advertenties

| Agent | Wat die doet |
|---|---|
| `advertentie-strateeg` | Ontwikkelt de advertentiestrategie: kanalen, budgetverdeling, funnelopbouw en doelen. |
| `campagne-specialist` | Plant en voert advertentiecampagnes uit: structuur, doelgroepen, advertenties en instellingen. |
| `advertentie-optimalisator` | Optimaliseert lopende campagnes en advertenties op basis van data. |
| `lead-generator` | Vindt en kwalificeert nieuwe leads: leadmagnets, formulieren, kwalificatiecriteria en opvolging. |
| `retargeting-specialist` | Brengt bezoekers terug naar de website met retargetingcampagnes. |

### 🔷 E-mail & Conversie

| Agent | Wat die doet |
|---|---|
| `email-strateeg` | Ontwikkelt de e-mailstrategie en automatiseringen: lijstopbouw, segmentatie, flows en nieuwsbriefritme. |
| `email-copywriter` | Schrijft converterende e-mails: onderwerpregels, preheaders, body en CTA. |
| `automatiserings-expert` | Bouwt e-mailflows en triggers uit tot technische specificaties voor tools als Brevo, Mailchimp, ActiveCampaign of HubSpot. |
| `conversie-specialist` | Optimaliseert landingspagina's en conversiepaden. |
| `ab-tester` | Ontwerpt en beoordeelt A/B-tests voor pagina's, mails en advertenties. |

### 💚 Data & Rapportage

| Agent | Wat die doet |
|---|---|
| `data-analist` | Analyseert marketingdata en rapporteert inzichten. |
| `dashboard-specialist` | Maakt duidelijke dashboards als HTML of specificatie voor Looker Studio, Google Sheets of een BI-tool. |
| `kpi-specialist` | Definieert en monitort de belangrijkste KPI's per doel, kanaal en afdeling. |
| `rapportage-expert` | Maakt heldere rapportages en adviezen voor stakeholders. |
| `roi-specialist` | Meet en verbetert het marketingrendement: kosten, opbrengsten, CAC, LTV en ROI per kanaal. |

## Voorbeelden

```
/marketing lanceer mijn nieuwe workshop 'AI voor kmo's' in november, budget 500 euro
```
```
Laat de concurrentie-analist drie concurrenten vergelijken: [namen].
```
```
Laat de data-analist deze export analyseren: marketing/data/export.csv
```
```
Laat de email-strateeg en de email-copywriter samen een welkomstflow van 5 mails maken.
```

## Hoe het werkt

- Elke agent staat in `.claude/agents/<naam>.md` met frontmatter (`name`, `description`, `tools`, `model`) en een systeemprompt.
- Claude Code kiest automatisch de juiste agent op basis van de `description`, of je noemt de agent bij naam.
- Subagents kunnen zelf geen andere subagents starten. Daarom levert de Strateeg een plan op en voert de hoofdsessie (via `/marketing`) de agents in volgorde uit.
- Onderzoeks-agents gebruiken `opus` of `sonnet` afhankelijk van de zwaarte. Pas `model:` aan naar wens.

## Aanpassen

- Nieuwe agent: kopieer een bestand in `.claude/agents/`, pas naam, beschrijving en werkwijze aan.
- Andere taal: vertaal de prompts, of vraag Claude Code om dat te doen.
- Eigen tools of MCP-servers: voeg ze toe aan `tools:` in de frontmatter.

## Structuur

```
.claude/
  agents/        41 agents
  commands/      /marketing
voorbeelden/asklien/  volledige voorbeeldrun
marketing/
  merk.md        jouw merkbasis
  doelgroep.md   jouw doelgroep
  doelen.md      jouw doelen
  <afdeling>/    output van het team
CLAUDE.md        afspraken voor alle agents
```

## Licentie

MIT. Gebruik het, pas het aan, deel het.

Gemaakt door Lien Pletinckx, [AskLien.ai](https://www.asklien.ai).
