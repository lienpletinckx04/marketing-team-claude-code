# Marketingteam in Claude Code

Deze repo bevat een compleet marketingteam als Claude Code-subagents: 1 CEO (de Strateeg) en 40 specialisten in 8 afdelingen. De agents staan in `.claude/agents/`.

## Hoe je het team gebruikt

- Grote vraag of meerdere afdelingen nodig: typ `/marketing <doel>`. De Strateeg maakt een plan en de hoofdsessie voert de agents uit.
- Eén specifieke taak: vraag rechtstreeks om een agent, bijvoorbeeld "laat de copywriter een landingspagina schrijven voor ...".
- Claude kiest ook zelf de juiste agent op basis van de beschrijving in de frontmatter.

## Merkbasis

Vul deze bestanden in voor je het team inzet. Elke agent leest ze eerst.

- `marketing/merk.md`: wie je bent, wat je doet, tone of voice, huisstijl.
- `marketing/doelgroep.md`: voor wie je werkt, pijnpunten, wensen.
- `marketing/doelen.md`: wat je de komende periode wil bereiken, met cijfers.

## Afspraken voor alle agents

- Alles in het Nederlands, concreet, zonder jargon.
- Geen verzonnen cijfers. Bron en datum bij elk feit.
- Output opslaan in `marketing/<afdeling>/` en het bestandspad noemen.
- Elke agent sluit af met: wat gedaan, belangrijkste conclusie, volgende stap.

## Mappen

```
.claude/agents/        de 41 agents
.claude/commands/      /marketing
marketing/             merkbasis en output van het team
```
