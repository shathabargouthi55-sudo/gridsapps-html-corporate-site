# Day 02 — Exit Ticket

**1. What did I build today?**

I built a multi-page HealthLink website using HTML5. It includes Home, About, Services, Blog, Contact, and Registration pages, along with contact and registration forms.

**2. What bug or difficulty did I solve?**

I worked on connecting the pages using relative paths and ensuring that the navigation links worked across the website.

**3. What concept can I explain clearly?**

I can explain HTML forms, labels, input types, fieldsets, legends, and native HTML5 validation using attributes such as `required`, `pattern`, and `minlength`.

**4. What remains incomplete?**

The forms currently provide front-end validation only. They are not connected to a backend to process submissions or create user accounts.
## Day 03 — CSS Foundations, Cascade & Box Model

**1. What did I build today?**

I created an external stylesheet (`assets/css/style.css`) and linked it to all pages of the HealthLink website, with no inline styles. I defined design tokens (colors, spacing, and font) as CSS variables in `:root` and used them throughout the stylesheet. I then styled the header and navigation, the hero section, the cards, the footer, and the services table.

**2. What bug or difficulty did I solve?**

The hero section was not styled because its closing `</section>` tag was on the same line as the opening tag, so the section was empty and its content sat outside it. I fixed the HTML structure and the styles applied correctly. I also made sure the stylesheet was linked with the correct path in every page.

**3. What concept can I explain clearly?**

- **CSS variables (design tokens):** I define a value once in `:root` and reuse it with `var(--name)`, so changing a color or spacing value in one place updates the whole website.
- **The box model:** every element is a box made of content, padding (space inside), border, and margin (space outside).
- **`box-sizing: border-box`:** by default, `width` measures only the content, so padding and border are added on top and the element becomes wider than expected. With `border-box`, the width includes the content, padding, and border, so the size I write is the real size of the element.

**4. What remains incomplete?**

The specificity debugging challenge is not completed yet. I still need to practice how the cascade and specificity decide which CSS rule wins. The other pages (About, Blog, Contact, Registration) only have the shared base, header, and footer styles for now.
## Day 04 — Flexbox, Grid & Responsive Design

**1. What did I build today?**

I made the HealthLink site responsive. I built a responsive navbar with Flexbox and a card grid with CSS Grid that shows 1, 2, or 3 columns depending on the screen size. I also took mobile, tablet, and desktop screenshots.

**2. What bug/difficulty did I solve?**

I checked the pages at different screen sizes and made sure there was no horizontal scrolling. I also changed the cards from Flexbox to Grid so the columns change clearly at each screen size.

**3. What concept can I explain clearly?**

Media queries apply CSS only at certain screen widths. I use Flexbox to arrange items in one line (like the navbar) and Grid to arrange items in rows and columns (like the cards).

**4. What remains incomplete?**

---------------