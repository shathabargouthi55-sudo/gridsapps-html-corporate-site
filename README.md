# HealthLink — Multi-Page Corporate Website

A multi-page website for HealthLink, a fictional digital health company. Built as part of the Grids Apps Full Stack Web Development Internship (HTML5 and CSS foundations).

## Pages

- **Home** (`index.html`) — Introduction to HealthLink and its services.
- **About** (`about.html`) — Company mission, vision, and core values.
- **Services** (`services.html`) — Digital healthcare services and a service overview table.
- **Blog** (`blog.html`) — Articles about digital healthcare and technology.
- **Contact** (`contact.html`) — Contact form with HTML5 native validation.
- **Registration** (`registration.html`) — Registration form with grouped controls and HTML5 validation.

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
- Styled header and navigation, hero section, cards, and footer.

## Technologies

- HTML5
- CSS3 (custom properties)

## Project Structure

```text
gridsapps-html-corporate-site/
├── assets/
│   ├── css/style.css
│   ├── images/
│   ├── icons/
│   └── js/
├── docs/
│   └── exit-tickets.md
├── index.html
├── about.html
├── services.html
├── blog.html
├── contact.html
├── registration.html
└── README.md


## How to Run

1. Clone or download the repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` using Live Server or directly in a web browser.

## Important Notes

The contact and registration forms demonstrate front-end HTML5 validation only. They are not connected to a backend, so messages are not sent and accounts are not created.

## Author

Shatha Abdelmajeed