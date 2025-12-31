# A.Inter Construction

Corporate website for A.Inter Construction Company Limited (บริษัท เอ.อินเตอร์คอนสตรัคชั่น จำกัด).

**Live Site:** https://a-inter-construction.vercel.app/

## Features

- Bilingual support (Thai/English)
- Portfolio showcase with project filtering
- Responsive design with mobile hamburger menu
- Contact form
- Image optimization via Astro

## Pages

- **Home** - Company overview, stats, and services
- **Portfolio** - Project gallery with category filtering
- **About** - Company vision, values, and capabilities
- **Contact** - Contact form and company information

## Tech Stack

- [Astro](https://astro.build/) - Static site generator
- TypeScript
- CSS (custom properties)

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Install dependencies                        |
| `npm run dev`     | Start local dev server at `localhost:4321`  |
| `npm run build`   | Build production site to `./dist/`          |
| `npm run preview` | Preview build locally before deploying      |

## Project Structure

```
src/
├── assets/          # Images
├── components/      # Reusable components
├── i18n/            # Translations and localized content
├── layouts/         # Page layouts
└── pages/
    ├── en/          # English pages
    └── *.astro      # Thai pages (default)
```
