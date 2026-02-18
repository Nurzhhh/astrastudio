# Astra Studio

Landing page for **Astra Studio** — beauty salon in Rudny, Kazakhstan.

**Website:** [astrastudio.kz](https://astrastudio.kz)

## About

Astra Studio offers manicure, lash extensions, brow services, massage and body contouring. The site serves as the main online presence for client acquisition and WhatsApp bookings.

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- No frameworks or build tools
- Google Fonts: Cormorant Garamond, Jost
- Fully responsive (mobile-first priority)

## Structure

```
├── index.html              # Main page
├── css/
│   └── style.css           # All styles (CSS variables, BEM)
├── js/
│   └── main.js             # Interactions (header, menu, animations)
└── images/
    ├── logos/               # Brand logos (black & white versions)
    └── workers/             # Owner photo & certificates
```

## Running Locally

Open `index.html` in a browser. No install or build required.

## Editing Prices

Service prices are in `index.html` inside `<ul class="service-list">` blocks. Each item follows:

```html
<li class="service-list__item">
  <span class="service-list__name">Service name</span>
  <span class="service-list__price">from X ₸</span>
</li>
```

## Contacts

- **Address:** Rudny, Komsomolsky Prospekt, 37
- **Phone / WhatsApp:** +7 708 754 50 93
- **2GIS:** [go.2gis.com/b54vO](https://go.2gis.com/b54vO)
