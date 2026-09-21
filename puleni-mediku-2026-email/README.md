# ✨ Půlení medíků 2026 – Email Template (Euphoria Edition) ✨

HTML newsletter e-mailová pozvánka na **Půlení medíků 2026** (Lékařská fakulta Ostravské univerzity) v klubu Fabric Ostrava s tématem **Euphoria**.

---

## 🎨 Vizuální styl & Euphoria téma
- **Paleta**: Hluboká noční indigo (`#0c0522`), ametystová fialová (`#140938`), neonová magenta/růžová (`#f472b6`), levandulová zář (`#c084fc`, `#f0abfc`).
- **Třpytivé akcenty**: Glitry, stardust prvky (`✦`, `✨`, `✧`), neonové záře a zvýrazněný dresscode box.
- **Slovníková definice**: Stylizovaný blok definující *euphoria* v kontextu medického studia.
- **Interaktivní CTA**: Zářivé tlačítko s gradientem a stínováním.

---

## ✉️ 100% Kompatibilita s Microsoft Outlook & Dark Theme

Šablona je navržena podle standardů pro e-mailové klienty s důrazem na **Microsoft Outlook** (desktop i web) a tmavé režimy:

1. **Microsoft Outlook Desktop (MSO / Word Rendering Engine)**:
   - Podmíněné MSO tabulky (`<!--[if (gte mso 9)|(IE)]>`) s fixní šířkou 600 px.
   - Bulletproof VML zaoblené tlačítko (`<v:roundrect>`) s přesným centrováním textu.
   - Pevně stanovené fallback fonty a `mso-table-lspace: 0pt; mso-table-rspace: 0pt;`.
   - Všechny barvy podložené atributem `bgcolor` i inline CSS `background-color`.

2. **Dark Theme & Inversion Fallbacks**:
   - Meta tagy `color-scheme` a `supported-color-schemes`.
   - Podpora `@media (prefers-color-scheme: dark)`.
   - Selektory pro Outlook.com / O365 Web Dark Mode (`[data-ogsc]`, `[data-ogsb]`).
   - Zachování sytého kontrastu bez vyblednutí při automatické inverzi barev.

---

## 📁 Struktura souborů

```
.
├── puleni-mediku-2026.html   # Hlavní HTML e-mailová šablona
├── images/                   # Obrazové podklady (hero, heartbeat EKG, gradienty)
│   ├── hero.jpg
│   ├── heartbeat.jpg
│   ├── gradient-top.png
│   └── gradient-bottom.png
└── README.md
```

---

## 🚀 Odeslání
Při odesílání přes rozesílací nástroje (např. Mailchimp, Ecomail, SmartEmailing, Sendinblue) nebo přímo přes Outlook zůstanou zachovány veškeré VML prvky a responzivní zobrazení.
