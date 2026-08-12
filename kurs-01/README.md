# Kom igång med Cowork

En interaktiv introduktionskurs på tre timmar om Claude Cowork, riktad till
lärare som undervisar i IT och AI, arbetar under strikta dataskyddskrav och
underhåller kursmaterial i HTML för Moodle.

**Kursen ligger här:** `index.html` — sajtens startsida.

## Innehåll

| Sökväg | Vad det är |
|---|---|
| `index.html` | Själva kursen. 8 pass, 21 flervalsfrågor med facit, 9 övningar. |
| `filer/ai-grundkurs-v3.zip` | Övningspaketet som används från pass 3. |
| `filer/kurspaket-uppdatering.skill` | Färdig Cowork-skill — facit till pass 5. |
| `ovningsmaterial/ai-grundkurs-v3/` | Samma övningspaket uppackat, så det går att bläddra live. |
| `.nojekyll` | Stänger av Jekyll-bearbetningen på GitHub Pages. |

## Publicera på GitHub Pages

1. Skapa ett repo och lägg innehållet i den här mappen i repots rot.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, mapp `/ (root)`.
3. Sajten dyker upp på `https://<användarnamn>.github.io/<repo>/` inom någon minut.

Kursen fungerar lika bra lokalt — öppna `index.html` direkt i webbläsaren.

## Tekniska noter

- Kurssidan är helt självständig: all CSS är inline, ingen JavaScript, inga
  externa bilder eller typsnitt. Interaktiviteten bygger på `<details>` och
  vanliga formulärelement.
- Innehållet i `index.html` kan därför också klistras in i Moodles redigerare
  utan att formateringen försvinner. Kopiera allt från den yttersta `<div>`
  till dess avslutande `</div>`.
- Kryssrutor och radioknappar sparar ingenting. Det finns ingen spårning,
  inga cookies och inga externa anrop på sajten.

## Om övningsmaterialet

`ai-grundkurs-v3` är **helt fiktivt** och innehåller med flit ett tjugotal fel:
föråldrade faktapåståenden, två stilmallar som krockar, trasiga länkar, en
saknad bild och tillgänglighetsbrister. Länkar som ger 404 gör det avsiktligt
— de är en del av uppgiften. Facit finns i pass 3 i kursen.

Inga verkliga personer, organisationer, studerande eller personuppgifter
förekommer någonstans i materialet. "Yrkeshögskolan Exempelia" och
"Nordkraft Ab" är påhittade.

## Licens

Materialet får användas, ändras och delas fritt.
