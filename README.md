# AccessibilityPractice

This repository contains a single **`index.html`** file that showcases a wide range of accessible HTML components. It demonstrates how to implement **ARIA roles**, **ARIA attributes**, and **semantic HTML** to build inclusive web content that works better for screen readers and assistive technologies.

## What’s Included

The HTML file includes fully accessible versions of:

### Semantic Elements
- Proper use of landmarks: `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`
- Use of headings (`<h1>`–`<h6>`) in proper hierarchy

### Interactive Components
- **Accordion**
  - Implemented using buttons and `aria-expanded`
  - Associated regions with `aria-controls` and `role="region"`

- **Show/Hide Toggle Sections**
  - Buttons with `aria-expanded`, `aria-controls`

- **Alert Messages**
  - Live regions using `role="alert"` and `aria-live="assertive"`

- **Navigation Menu**
  - `<nav>` with `role="navigation"` and labeled using `aria-label`
  - Keyboard-focusable links

- **Modal Dialog**
  - Proper `role="dialog"` or `role="alertdialog"`
  - Focus trapping
  - `aria-modal`, `aria-labelledby`, and `aria-describedby`

- **Form Elements**
  - Labels associated with inputs
  - ARIA attributes for error messaging (`aria-invalid`, `aria-describedby`)
  - `role="form"` and field grouping with `fieldset` and `legend`

### Accessibility Practices Followed
- Logical tab order
- Visible focus indicators
- Proper screen reader guidelines

## Purpose

The goal of this demo is to:
- Showcase how to make HTML element accessible
- Educate developers on using ARIA and semantic elements correctly
- Provide a reference boilerplate for accessible components

## Contributions

Feel free to fork this repo and extend accessibility examples or add your improvements.  
Pull requests welcome!

---

**Accessibility matters. Let's build web for everyone.**
