# Kursbibliotek

Ett repo för alla självstudiekurser. Portalen på förstasidan länkar till tjugo
platser; fyll dem efter hand.

## Struktur

```
index.html      Portalen. Listan över kurser redigeras här.
.nojekyll       Stänger av Jekyll-bearbetningen på GitHub Pages.
kurs-01/ … kurs-20/
                En mapp per kurs. Tomma tills du fyller dem.
```

## Lägga till en kurs

1. Lägg kursens `index.html` i rätt mapp, till exempel `kurs-05/index.html`.
   Eventuellt material läggs i undermappar under samma mapp.
2. Öppna `index.html` i repots rot och leta upp kommentaren
   `===== KURSLISTA – REDIGERA HÄR =====`.
3. Hitta blocket som börjar med `<!-- KURS 05 -->` och ändra tre rader:
   titeln, beskrivningen och tidsangivelsen.
4. Byt etiketten från *Ledig plats* till *Publicerad*: ersätt
   `background:#e8e0d4;color:#8a7e6e` med `background:#1e2a3a;color:#f0ece4`
   och byt texten.
5. Radera `LAS-MIG.txt` ur mappen.

Länken behöver du inte röra. Den pekar redan på `kurs-05/index.html`.

## Publicera på GitHub Pages

Lägg **innehållet** i den här mappen i repots rot, inte mappen själv. Sedan
Settings → Pages → Source: *Deploy from a branch*, branch `main`, mapp `/ (root)`.

## Noter

- Lediga platser ger 404. Det är avsiktligt — mappen finns, sidan gör det inte ännu.
- Varje tom mapp innehåller en `LAS-MIG.txt`. Den behövs för att git ska ta med
  mappen alls; git spårar inte tomma mappar.
- Portalen och kurserna är helt självständiga: inline CSS, ingen JavaScript,
  inga externa bilder eller typsnitt. Inga externa anrop, inga cookies.
- Vilka mappar som är lediga håller du reda på själv. Etiketten på portalen är
  din enda anteckning, så håll den uppdaterad.
