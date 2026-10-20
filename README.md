# Ghost in the OT — event site

One-page, Persian (RTL) site for the **"پنجره‌ای به‌سوی OT"** seminar, fully responsive, from small phones to wide desktops.
Plain HTML, CSS and JavaScript in a single file. No Docker, no build step, no dependencies.

## Open it

Double-click **`index.html`**. That's it.

- It scrolls like a normal website on every device: one column on phones and tablets, a two-column hero on desktop.
- Keep `index.html` next to the `assets/` and `favicon.svg` files (images and the font load from there).

## Before launch

1. **Registration links:** in `index.html`, search for `registration-form-1` and `registration-form-2` and replace those two `https://example.com/...` links with the real forms. You can also rename the two cards ("ثبت‌نام حضوری" / "ثبت‌نام آنلاین") if the forms are for something else.
2. **Countdown date:** `EVENT_START` at the top of the `<script>` block at the bottom of `index.html`.
3. Replace `assets/img/instructor.jpg` (square, at least 600x600) and `assets/img/mascot.png` / `.webp` with the original, higher-resolution files.
4. Review all copy, especially the "Why this course" cards.

## Deploy

Upload `index.html`, `favicon.svg` and `assets/` to any static host (cPanel, GitHub Pages, Netlify...).

## Credits

Font: [Vazirmatn](https://github.com/rastikerdar/vazirmatn), SIL Open Font License (`assets/fonts/OFL.txt`).
