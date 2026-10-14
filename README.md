# FIN ARS Design 2.2

Sodobna spletna predstavitev arhitekturnega biroja **FIN ARS d.o.o.** (Zagorje ob Savi).

## O projektu

Prenova spletne strani www.finars.si v sodobnem, odzivnem dizajnu z:

- Animiranim ozadjem (slideshow arhitekturnih slik)
- Podstranmi: Domov, Projekti, Galerija, Info, Zgodovina, Novice, Kontakt
- Zoom ob kliku na slike (lightbox)
- Animacijami in modernim UI
- Podatki o podjetju iz javnih virov (AJPES, obstoječa spletna stran)

## Struktura

```
├── index.html          # Domov
├── projekti.html       # Projekti (z zoom)
├── galerija.html       # Galerija arhitekture (z zoom)
├── info.html           # O podjetju
├── zgodovina.html      # Zgodovina in pretekli projekti
├── novice.html         # Novice 2026
├── kontakt.html        # Kontakt
├── css/style.css
├── js/main.js
└── README.md
```

## Zagon

Odprite `index.html` v brskalniku ali uporabite lokalni strežnik:

```bash
npx serve .
```

## GitHub Pages

Za objavo na GitHub Pages: Settings → Pages → Source: main branch / root.

## Podatki o podjetju

- **FIN ARS Center za arhitekturo, gradbeno projektiranje in druge storitve d.o.o.**
- Podvine 36, 1410 Zagorje ob Savi
- Matična št.: 2144921000 | Davčna: SI 70790817
- info@finars.si | 03 566 05 46

© 2026 – Design 2.2
