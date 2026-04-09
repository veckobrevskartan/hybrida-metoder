# Svensk OSINT – Hybridmethods

Interaktiv visualisering av hybrida metoder och incidenter kopplade till säkerhetsanalys.

## Filer

| Fil | Storlek | Beskrivning |
|-----|---------|-------------|
| `index.html` | ~36 KB | Huvudfil – all UI, logik och visualisering |
| `events.js` | ~607 KB | Händelsedata (1 115 incidenter) |

## Upplägg på GitHub Pages

1. Lägg båda filerna i roten av ditt GitHub-repo
2. Gå till **Settings → Pages**
3. Välj **Source: Deploy from a branch → main → / (root)**
4. Spara — sidan är tillgänglig på `https://<användarnamn>.github.io/<repo>/`

## Vyer

- **Spektrum** – Händelser placerade längs konfliktspektrumet (Krig / Gråzon / Fred), organiserade efter hybridmetod. Filtrera på nivå, kategori, land och år. Klicka en prick för detaljpanel.
- **Lista** – Tabellvy med alla händelser, sorterbar via filter i vänsterpanel.
- **Mindmap** – Interaktiv markmap-träd med alla kategorier. Klicka en kategori för att expandera och se klickbara händelselänkar till originalkällor.

## Källdata

Händelsedata härstammar från Svensk OSINTs veckobrev. Blå prickar = Sverige (SE), röda = övriga länder.
