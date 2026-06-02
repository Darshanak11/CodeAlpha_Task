# Darshana K — Personal Portfolio

A single-file personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. Dark editorial aesthetic with gold accents, smooth animations, and a fully responsive layout.

---

## Live Preview

Open `portfolio.html` directly in any modern browser — no build step, no dependencies, no server required.

---

## Features

- **Single-file** — everything (HTML, CSS, JS) lives in one `portfolio.html` file
- **No framework / no build tool** — zero npm, zero bundler, zero config
- **Fully responsive** — mobile, tablet, and desktop layouts
- **Smooth scroll** — native CSS `scroll-behavior: smooth` on all anchor links
- **Scroll-triggered animations** — sections and elements fade up as they enter the viewport via `IntersectionObserver`
- **Custom cursor** — a gold dot + trailing ring that reacts to hoverable elements
- **Animated skill bars** — percentage bars animate in on scroll
- **Sticky navbar** — changes background and padding on scroll
- **Mobile hamburger menu** — animated open/close with full-screen overlay
- **Contact form** — client-side with a simulated submit and toast notification
- **Active nav highlighting** — current section is highlighted as you scroll

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen intro with headline, tagline, CTA buttons, and scroll indicator |
| **About** | Two-column layout with photo placeholder, stat counters, and bio |
| **Skills** | Four skill cards with animated progress bars and tech lists |
| **Projects** | Asymmetric grid of five project cards (large / small / full-width) |
| **Resume** | Two-column timeline for work experience and education/certifications |
| **Contact** | Centered contact form + social media links |
| **Footer** | Simple one-liner |

---


## File Structure

```
portfolio/
├── portfolio.html   # entire site (HTML + CSS + JS)
├── README.md        # this file
```

---

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). The custom cursor is hidden on touch devices via pointer events.

---

## License

MIT — free to use, modify, and redistribute.
