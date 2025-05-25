# Semantic HTML, SEO, Accessibility & SCSS Best Practices
 
## Semantic HTML

Semantic HTML provides meaningful structure to web pages, making them more understandable for browsers, screen readers, and developers.

### Best Practices

- Use tags that match the content:
  - `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<aside>`
- Use `<button>` instead of clickable `<div>` or `<span>`
- Use `<label for="id">` when pairing labels with form inputs
- Use heading hierarchy properly: `<h1>` once per page, followed by `<h2>`, `<h3>`, etc.

---

## SEO Best Practices

Good SEO improves your site's visibility on search engines.

### Best Practices

- Use unique and descriptive `<title>` and `<meta description>` tags
- Use proper heading structure with keywords in mind
- Use `alt` attributes for all images
- Avoid duplicate content
- Use canonical URLs if needed
- Structure content using semantic tags
- Add `lang="en"` to your HTML tag if content is in English

---

## Accessibility (a11y)

Accessibility ensures your website can be used by everyone, including users with disabilities.

### Best Practices

- Ensure sufficient color contrast (WCAG AA or AAA)
- Use semantic HTML (helps screen readers)
- Always provide `alt` text for images
- Use ARIA attributes only when necessary
- Ensure forms have associated labels
- Ensure all interactive elements are keyboard accessible
- Add `role` attributes where applicable (e.g., `role="button"` for custom elements)
- Use skip navigation links (`<a href="#main">Skip to main content</a>`)

---

## SCSS/SASS Styling

SASS (`.scss`) makes writing CSS more powerful and modular.

### ✅ Best Practices

- Use variables for colors, font sizes, spacing, etc.  
  ```scss
  // _variables.scss
  $primary-color: #0d6efd;
  $font-stack: 'Inter', sans-serif;
