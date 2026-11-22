# Chatter — HTML & CSS Figma implementation

A responsive, static implementation of the original Chatter landing page supplied as a screenshot and eight Figma-exported SVG sections.

## Run

Open `index.html` in any modern browser. No installation, build step, or JavaScript framework is needed. The only remote resource is an optional Google Fonts stylesheet; fallback fonts work offline.

## Files

- `index.html` — semantic page markup and anchor navigation
- `styles.css` — desktop layout and mobile breakpoints
- `assets/` — the *original* photographs extracted from the supplied SVG files and exact vector feature icons. The photos are compressed locally for loading performance.

## Notes

- Navigation links move to corresponding sections. Sign-up, log-in, and content creation require real routes/backend to become functional.
- No edits were made to the Figma source file.
- The supplied SVG sections contain outlined text, so text is recreated in HTML using the close Poppins family to keep it selectable and accessible.
