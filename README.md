# Umferðarmerkin

Vafraforrit til að læra íslensku umferðarmerkin, bæði flokkana og hvað hvert
merki þýðir. Engin uppsetning – opnaðu `index.html` í vafra.

- **Læra:** flokkarnir 100–900 samkvæmt reglugerð nr. 250/2024 um umferðarmerki
  og notkun þeirra (hlutverk, útlit og minnisregla) og öll merki hvers flokks.
  Smelltu á merki til að lesa merkinguna.
- **Leikir:**
  - *Hvaða flokkur?* – sjáðu merki og veldu flokkinn.
  - *Hvað þýðir merkið?* – sjáðu merki og veldu rétta merkingu af fjórum.
  - *Finndu merkið* – sjáðu heiti og veldu rétta merkið af fjórum.
  - *Blandað próf* – allt í bland.

  Hægt er að velja hvaða flokkar eru með og fjölda spurninga. Í lokin sérðu
  villurnar með skýringum og getur æft þær sérstaklega. Lyklaborð: <kbd>1</kbd>–<kbd>9</kbd>
  velja svar, <kbd>Enter</kbd> næsta spurning. Besti árangur er geymdur í `localStorage`.

## Skrár

- `index.html` – síðan
- `merki.js` – flokkar og merki; merkin eru teiknuð sem SVG (einfaldaðar myndir).
  Hér er auðvelt að bæta við merkjum eða leiðrétta lýsingar. Merkjanúmer (`nr`)
  eru aðeins skráð þar sem þau hafa verið staðfest.
- `leikur.js` – viðmót og leikir
- `style.css` – útlit (ljóst og dökkt)

## Birta á vefnum

Í *Settings → Pages* á GitHub: veldu *Deploy from a branch*, greinina `main` og
möppuna `/ (root)`. Þá verður leikurinn aðgengilegur á
https://ragnarthorp.github.io/umferd/
