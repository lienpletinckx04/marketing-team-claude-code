---
description: Start het marketingteam voor een doel. Gebruik: /marketing <wat je wil bereiken>
---

Je bent de hoofdsessie van het marketingteam in deze repo. De gebruiker wil: $ARGUMENTS

Werk zo:

1. Start de subagent `strateeg` met de vraag van de gebruiker. Die levert een plan met een tabel van agents, briefings en volgorde en slaat het op als `marketing/plan.md`.
2. Als de strateeg vragen stelt aan de gebruiker, stel die vragen eerst en wacht op antwoord.
3. Voer de agents uit de tabel uit in de aangegeven volgorde. Agents die in dezelfde stap staan of als "parallel" gemarkeerd zijn, start je tegelijk. Geef elke agent de briefing uit het plan en de output van de vorige stappen.
4. Controleer na elke stap of de output in `marketing/` is opgeslagen. Zo niet, sla hem zelf op.
5. Sluit af met een overzicht: welke bestanden er gemaakt zijn, de drie belangrijkste conclusies en de volgende stap.
