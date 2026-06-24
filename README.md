# Florilegium

*A gathering of flowers* — a digital herbal of 166 plants and flowers, their names, their virtues, and the lore grown up around them.

## About

Florilegium is a searchable, illustrated compendium of botanical folklore, etymology, and history, drawn from sources ranging from Pliny and Dioscorides through the great herbals of Gerard, Parkinson, and Culpeper to the folklore collections of Frazer, Folkard, and Vickery.

Each entry includes:

- **Etymology** — the roots and stories behind the common and botanical names
- **Virtues** — traditional medicinal and practical uses
- **Lore** — folklore, superstition, and symbolism from across cultures
- **History** — the plant's role in human events
- **Botanical description** — identifying features and habitat
- **Sources** — cited references for further reading

Entries are accompanied by photographs from Wikimedia Commons and generative SVG botanical illustrations.

## Features

- Full-text search across names, folk-names, and virtues
- Filter by theme: medicinal, protective, love & lore, edible, sacred, funerary, trees, dye & craft
- Alphabetical index with 166 entries spanning A to Z
- Light and dark themes with OS preference detection
- Individual shareable pages for each plant
- Responsive layout for desktop and mobile

## Structure

```
Florilegium/
├── index.html        Main page (GitHub Pages entry point)
├── icon.svg          App icon
├── css/
│   └── style.css     Stylesheet with light/dark theme variables
├── js/
│   └── main.js       Application logic, plant data, and SVG art generator
├── images/           539 WebP photographs and thumbnails
└── pages/            166 individual plant pages
```

## Running locally

Serve from the project root with any static file server:

```
npx http-server . -p 8080
```

Then open `http://localhost:8080`.

## License

[MIT](LICENSE)
