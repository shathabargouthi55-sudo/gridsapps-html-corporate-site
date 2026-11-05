# HealthLink — Multi-Page Corporate Website

A multi-page website for HealthLink, a fictional digital health company. Built as part of the Grids Apps Full Stack Web Development Internship (HTML5 and CSS foundations).

## Pages

- **Home** (`index.html`): Introduction to HealthLink and its services.
- **About** (`about.html`): Company mission, vision, and core values.
- **Services** (`services.html`): Digital healthcare services and a service overview table.
- **Blog** (`blog.html`): Articles about digital healthcare and technology.
- **Contact** (`contact.html`): Contact form with HTML5 native validation.
- **Registration** (`registration.html`): Registration form with grouped controls and HTML5 validation.

## Features

### HTML
- Semantic HTML5 structure using `header`, `nav`, `main`, `section`, `article`, and `footer`.
- Navigation links connecting all pages.
- Page-specific titles and meta descriptions.
- Forms using labels, appropriate input types, `fieldset`/`legend`, and native validation (`required`, `pattern`, `minlength`, `maxlength`).
- A service overview table with a caption and accessible column headings.
- Images with descriptive alternative text and captions.

### CSS
- A single external stylesheet (`assets/css/style.css`) shared by all pages, with no inline styles.
- Design tokens defined as CSS variables in `:root` (colors, spacing, typography).
- Global `box-sizing: border-box` reset.
- Styled header and navigation, hero section, cards, footer, and table.

### Responsive Design
- Responsive navbar using Flexbox: the logo and links stack and wrap on small screens.
- Mobile-first card grid using CSS Grid: 1 column on mobile, 2 columns from 600px, and 3 columns from 992px.
- Media queries for tablet and desktop layouts.
- Checked for horizontal overflow on mobile.

## Screenshots

| Mobile | Tablet | Desktop |
|---|---|---|
| ![Mobile](screenshots/mobile.png) | ![Tablet](screenshots/tablet.png) | ![Desktop](screenshots/desktop.png) |

## Technologies

- HTML5
- CSS3 (custom properties, Flexbox, Grid, media queries)

## How to Run

1. Clone or download the repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` using Live Server or directly in a web browser.

## Important Notes

The contact and registration forms demonstrate front-end HTML5 validation only. They are not connected to a backend, so messages are not sent and accounts are not created.

## Author

Shatha Abdelmajeed