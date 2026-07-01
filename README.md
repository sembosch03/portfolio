# Portfolio — Sem Bosch

Persoonlijke portfolio + verkoop-site. Eén `index.html` (statisch, geen build) plus 4 werkende demo-projecten.

## Structuur

```
portfolio/
├── index.html              ← hoofdpagina (diensten + portfolio + contact)
├── demos/
│   ├── restaurant/         ← demo: restaurant-landingspagina (werkend reserveringsformulier)
│   ├── sportschool/        ← demo: sportschool-site (rooster + werkend inschrijfformulier)
│   ├── offerte/            ← demo: offerte-generator (live berekening + print/PDF)
│   └── vakman/             ← demo: schilder- & klusbedrijf-site (diensten, werk, reviews, offerteformulier)
└── README.md
```

Open `index.html` in je browser om alles te zien. Projectkaarten linken naar de demo's.

## Wat je nog invult (5 min)

In `index.html`, onderaan bij `<!-- VUL JE EIGEN GEGEVENS IN -->`:

| Placeholder | Vervang door |
|-------------|--------------|
| `JOUW@EMAIL.nl` | je echte e-mailadres |
| `wa.me/31600000000` | je 06 als `316XXXXXXXX` (zonder +) |
| `tel:+31600000000` | je 06 als `+316XXXXXXXX` |

Klopt de naam "Sem Bosch" niet? Zoek + vervang in `index.html` en de footers van de demo's.

## Gratis online zetten (10 min)

Kies één:

1. **Netlify Drop** — ga naar [app.netlify.com/drop](https://app.netlify.com/drop), sleep de hele `portfolio`-map erin → direct live URL. Simpelst.
2. **Vercel** — [vercel.com](https://vercel.com), import map → live. Mooiere naam voor werkgevers.
3. **GitHub Pages** — maak een repo, push deze map, zet Pages aan. Telt óók als portfolio-bewijs op je GitHub.

Tip: GitHub + Vercel samen = je toont werkgevers je code én een live site.

## Demo's vervangen door echte klanten

Zodra je een echte klus af hebt:
1. Vervang in `index.html` de tekst + emoji van een projectkaart door de echte case.
2. Zet de `href` naar de echte klant-URL.
3. Vraag de klant om een korte review → zet die erbij als testimonial.

Elke echte case maakt de volgende klant makkelijker. Vliegwiel.

## Demo-details (om aan klanten/werkgevers te laten zien)

- **Restaurant** — sticky nav, menu, openingstijden, reserveringsformulier met bevestiging. Volledig responsive.
- **Sportschool** — hero, statistieken, lesrooster-tabel, prijskaarten, inschrijfformulier. Neon/sport-stijl.
- **Offerte-generator** — typ links, offerte rechts wordt live opgebouwd; regels toevoegen/verwijderen, BTW-berekening, datums, één klik naar print/PDF. Toont écht JavaScript-werk.
- **Vakman (schilder & klusbedrijf)** — vertrouwen-gerichte site: diensten, voor/na-projecten, reviews, spoedbanner, offerteformulier met bevestiging. Bedoeld als pitch-bijlage voor schilder-/loodgieterprospects i.p.v. de generieke portfolio-link.
