# NTW.SaaS Landing Page

Single static HTML page (`pagina.html`) — dental clinic landing page. No build system, no dependencies, no package manager.

## Commands

- Preview: Open `pagina.html` directly in a browser.
- No dev server, linter, formatter, typechecker, or tests.

## Structure

- `pagina.html` is the only file — all CSS (inline `<style>`) and JS (inline `<script>`) are self-contained.
- Sections: hero, services (tratamentos), about, testimonials, contact form, footer.
- Responsive breakpoints: 1024px, 640px.
- Scroll-based nav shadow and IntersectionObserver fade-up animations.

## Conventions

- Use CSS custom properties (`:root` vars) for colors, spacing, fonts.
- Fonts: Playfair Display (headings), DM Sans (body), loaded via Google Fonts.
- Nav-links hidden on mobile (<640px) with no hamburger menu.
- Form is visual-only (no JS handler or backend endpoint wired).

## Editing

- All edits in `pagina.html`. Maintain existing CSS var references and responsive patterns.
- No external CSS/JS files — keep everything inline.
