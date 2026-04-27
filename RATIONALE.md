# Design Rationale

## HTML Structure
I structured the website using semantic HTML5 elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`. This ensures the content is logically organized and accessible to both users and assistive technologies. The navigation is placed inside `<nav>`, and each page’s main content is wrapped in `<main>`. Content blocks are grouped with `<section>` and `<article>` for clarity and meaning.

## CSS Layout & Organization
All styles are in a single, well-organized `style.css` file inside a `css` folder. I used Flexbox for layout, especially for the profile and skills sections, to ensure flexible and responsive arrangements. CSS is grouped by component (navigation, profile, skills, forms, etc.) and follows a consistent naming convention for maintainability.

## Accessibility
Accessibility is addressed by providing meaningful `alt` text for all images, using proper heading hierarchy (`<h1>`, `<h2>`, etc.), and associating `<label>` elements with form inputs. The navigation is keyboard-accessible, and the color contrast meets accessibility standards.

## Responsive Design
The site uses a mobile-first approach, with styles optimized for small screens by default. Media queries adjust the layout for larger screens (desktop), such as switching the profile section to a horizontal Flexbox layout. This ensures the site is usable and visually appealing on both mobile and desktop devices.

---

This approach demonstrates best practices in semantic HTML, CSS organization, accessibility, and responsive design, meeting all assignment requirements.