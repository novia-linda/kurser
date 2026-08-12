# Copilot 365 och skills

En interaktiv kurs byggd för att läsas i ett fönster medan man arbetar i ett annat.

## Innehåll

| Sökväg | Vad det är |
|---|---|
| `index.html` | Kursen. Sajtens startsida. |
| `copilot-365-och-skills-moodle.html` | Samma kurs, att klistra in i Moodles redigerare. |
| `filer/` | Nedladdningsbart material som hör till kursen. |
| `ovningsmaterial/` | Övningsmaterial, uppackat så det går att bläddra i. |
| `.nojekyll` | Stänger av Jekyll-bearbetningen på GitHub Pages. |

## Publicera på GitHub Pages

1. Lägg **innehållet** i den här mappen i repots rot, inte mappen själv.
2. Settings → Pages → Source: *Deploy from a branch*, branch `main`, mapp `/ (root)`.
3. Sajten dyker upp på `https://<användarnamn>.github.io/<repo>/` inom någon minut.

Kursen fungerar lika bra lokalt — öppna `index.html` i webbläsaren.

## Lägg in i Moodle

1. Öppna `copilot-365-och-skills-moodle.html` i en textredigerare och kopiera hela innehållet.
2. Skapa en sida i Moodle, växla redigeraren till HTML-läge och klistra in.
3. Ladda upp eventuellt material under `filer/` som filresurser i kursen.

All CSS ligger inline och det finns ingen JavaScript, så formateringen
överlever Moodles filtrering.

## Tekniska noter

- Sidan är helt självständig: inline CSS, ingen JavaScript, inga externa
  bilder eller typsnitt. Inga externa anrop, inga cookies, ingen spårning.
- Interaktiviteten bygger på `<details>` och vanliga formulärelement.
  Kryssrutor och svar sparas inte någonstans.
- Allt övningsmaterial är fiktivt. Inga verkliga personuppgifter förekommer.
