# Lathund – skills i Copilot 365

En sida att skriva ut och ha bredvid tangentbordet.

---

## Mallen

```
---
name: samma-som-mappens-namn
description: [Vad den gör i en mening.] Använd vid
  [tre till fem ord du faktiskt skriver].
---

# Rubrik

## Vad som ska produceras
Struktur, rubriker, ordning, ungefärlig längd.

## Krav som alltid gäller
Ton, språk, vad som aldrig får utelämnas. Förklara varför
när regeln är oväntad.

## Vad du inte ska göra
Skicka inget, ändra inte rubrikerna, hitta inte på siffror.

## Vid osäkerhet
Skriv [OKLART] i stället för att gissa. Lista allt du
markerat sist.

---
Ägare: [namn]. Ses över: [månad].
```

---

## Var skills bor

| Yta | Lagring | Anrop |
|---|---|---|
| Word, Excel, PowerPoint | Skills-mapp i OneDrive | Menyn eller `@skillnamn` |
| Samarbete | Under *Anpassa*, uppladdad | Automatiskt vid sessionsstart |
| Copilot i SharePoint | `Agent Assets/Skills/<namn>/SKILL.md` | Automatiskt eller vid namn |
| Färdiga från Microsoft | Följer med | `@brandkit` och liknande |

---

## Gränserna

| | |
|---|---|
| Ensam `.md`-fil | 1 MB |
| Arkiv, komprimerat | 10 MB |
| Arkiv, uppackat | 50 MB |
| Filer per arkiv | 100 |
| Format vid uppladdning | `.md`, `.zip`, `.skill` med SKILL.md i roten |

Du kommer inte i närheten av taken. En bra skill är sällan mer än en A4.

---

## Felsökning

| Symptom | Orsak | Åtgärd |
|---|---|---|
| Syns inte i listan | Mappnamn ≠ `name` | Rätta namnet. Överhoppningen sker tyst. |
| Syns men används inte | Session startade före skillen fanns, eller avstängd | Starta ny konversation, uppdatera listan |
| Triggar aldrig själv | Beskrivningen beskriver innehåll, inte tillfälle | Skriv om med dina egna ord |
| Fel skill triggar | Två beskrivningar överlappar | Gör dem åtskilda, eller slå ihop |
| Triggar men följs inte | För många eller motstridiga regler | Korta ner |

**Knepet:** anropa skillen uttryckligen med `@namn`.
Bra då men dåligt annars → **beskrivningen** är problemet.
Dåligt även då → **instruktionerna** är problemet.

---

## Aldrig i en SKILL.md

- Lösenord, nycklar, inloggningsuppgifter
- Personuppgifter — inte ens som exempel
- Dagens datum och terminens deadlines
- Detaljer som ändras varje kursomgång

De två första för att filen följer med och kan delas vidare. De två sista för
att de blir fel nästa termin — och då märker du det inte.

---

## Tolv beskrivningar att utgå från

Byt ut orden mot dina egna. Det viktiga är formen: *vad den gör* + *när*.

```
Skriver tentamensinstruktioner enligt vår mall. Använd vid tentamen,
inlämningsuppgift, uppgiftsbeskrivning, provinstruktion.

Gör veckobrev till studerande. Använd vid veckobrev, veckoinfo,
meddelande till klassen, information inför veckan.

Bygger bedömningsmatriser utifrån lärandemål. Använd vid matris,
bedömningskriterier, betygskriterier, rubrik för uppgift.

Skapar bildspel av befintligt kursmaterial. Använd vid presentation,
bildspel, slides, föreläsningsunderlag.

Granskar material mot tillgänglighetskraven. Använd vid tillgänglighet,
WCAG, alt-text, kontrast, granska material.

Skriver kursintroduktioner. Använd vid kursstart, introduktion till kursen,
välkomstbrev, första lektionen.

Gör frågebanker med flervalsfrågor. Använd vid quiz, prov, frågor till
kursen, självtest, kontrollfrågor.

Sammanställer kursutvärderingar. Använd vid utvärdering, kursfeedback,
studerandeenkät, sammanställ svaren.

Skriver mötesprotokoll ur råa anteckningar. Använd vid protokoll,
mötesanteckningar, renskriv anteckningarna.

Uppdaterar föråldrat kursmaterial. Använd vid uppdatera materialet,
modernisera kursen, faktagranska, stämmer detta fortfarande.

Gör uppgifter i tre svårighetsgrader. Använd vid differentiering,
lättare variant, svårare variant, anpassa uppgiften.

Skriver standardsvar till studerande. Använd vid svara på fråga,
återkommande fråga, mall för svar.
```

---

## Genvägen värd att minnas

Skriv inte skillen från grunden. **Gör uppgiften en gång som vanligt, och be
sedan om en skill av det som gjordes.** Du får ditt faktiska arbetssätt i
stället för din idealbild — och mycket av det du gör rätt är sådant du aldrig
formulerat.

Har du ett bra exempel liggande går det ännu fortare: be om en skill som
beskriver reglerna exemplet följer.

---

*Uppgifterna kontrollerades i augusti 2026 mot Microsofts dokumentation.
Allt exempelmaterial är fiktivt.*
