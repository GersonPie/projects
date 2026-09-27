# Gerson Tamele — Portfolio

Personal portfolio for **Gerson Humberto Tamele**, a full-stack developer focused on web, mobile, backend services, and digital products.

The site is available in English and Portuguese and follows a clean, content-first portfolio structure inspired by [Brittany Chiang's V3 portfolio](https://v3.brittanychiang.com/).

## Português

Portfólio pessoal de **Gerson Humberto Tamele**, desenvolvedor full-stack focado em soluções web, mobile, serviços backend e produtos digitais.

O site está disponível em português e inglês e apresenta competências técnicas, experiência profissional e projectos em destaque.

## Features / Funcionalidades

- English and Portuguese language switch
- Light and dark themes
- Saved language and theme preferences
- Responsive design for desktop, tablet, and mobile
- Accessible semantic HTML and keyboard-friendly controls
- Reduced-motion support
- Animated content reveal while scrolling
- Featured MilionStore presentation
- Professional experience and additional project sections
- No frameworks, packages, or build process required

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- CSS custom properties
- Intersection Observer API
- Local Storage API

## Project structure

```text
.
├── index.html   # Complete portfolio, styles, and interactions
└── README.md    # Project documentation
```

## Running locally

Because this is a static website, it can be opened directly:

1. Download or clone the project.
2. Open `index.html` in a modern browser.

For a local development server, you can also run:

```bash
npx serve .
```

Then open the address shown in the terminal.

## Customization

The entire website is contained in `index.html`.

- Update personal text inside the matching `.lang-en` and `.lang-pt` elements.
- Change theme colors in the CSS variables under `:root` and `html[data-theme="dark"]`.
- Add professional experience inside the `#experience` section.
- Add featured or additional work inside the `#projects` and `#other-projects` sections.
- Update contact and social links in the introduction, contact section, and footer.

When adding new text, include both language versions:

```html
<span class="lang-en">English text</span>
<span class="lang-pt">Texto em português</span>
```

## Featured work

- [MilionStore](https://milionstore-6b1cd.web.app/products)
- [MOVEZA](https://moveza-pi.vercel.app/)
- [Unione Solution](https://unionesolution.vercel.app/)
- [Gestor de Microcrédito](https://gestor-de-microcredito.vercel.app)
- [Unione Books Store](https://unione-solution-lda-books-store.vercel.app)

## Contact

- Email: [info.gersontamele@gmail.com](mailto:info.gersontamele@gmail.com)
- GitHub: [GersonPie](https://github.com/GersonPie)

## Deployment

The site can be deployed to any static hosting service, including GitHub Pages, Vercel, Netlify, or Firebase Hosting. No build command is required; publish the project root with `index.html` as the entry point.

## License

This portfolio and its content belong to Gerson Humberto Tamele. You may use the code as a learning reference, but personal information and project content should not be reused without permission.
