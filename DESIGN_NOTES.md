# Valery Valdyrev site redesign

## Reference study

Checked on 2026-09-16. `recoverymassage.ee` uses Big Shoulders Display for headings and navigation and Outfit for body copy. Its desktop hero is approximately one viewport high, with a 4rem uppercase name, 1.2rem spaced subtitle, 800px content sections, 60px section spacing, and a warm neutral palette (`#f5f3ef`, `#2c2825`, white cards and thin `#e5e0d8` borders). On screens below 768px, the name drops to 2rem, sections to 40px vertical padding and the navigation becomes a fullscreen menu.

This implementation keeps the calm hierarchy, generous spacing and minimal navigation but does not copy the reference assets. It now uses the same freely licensed Google Fonts as the reference: Big Shoulders Display for display type and Outfit for body copy. Both Google Fonts families are Latin/Latin-ext only, so the font stacks include Roboto Condensed and Montserrat as deliberate Cyrillic fallbacks on the Russian page.

The measured reference proportions used in the layout are: 64px desktop / 32px mobile hero H1, 19.2px hero subtitle, 16px CTA text with 6px tracking, 800px section boxes with 760px usable content, 60px desktop / 40px mobile section padding, and 25.6px desktop section headings.

## Content still needed

- A real portrait of Valery.
- A real photograph of Valery working.
- Photographs of the HINGA room and entrance.
- Confirmed training, qualification and practice-start details.
- Confirmed Instagram, Facebook and Stebby URLs.

## Easy replacements

- Main booking URL: search for `calendar.app.google` in the three HTML files.
- Hero placeholder image: replace `pexels-anntarazevich-6560304.jpg` or update its URL in `assets/styles.css`. The portrait area is intentionally image-free until a real Valery portrait is available.
- TODO comments are present in every language page near the biography and social links.
