# Apple-Style Reusable Nav Bar

A clean, translucent, Apple-inspired navigation bar built with Tailwind CSS. It uses a fixed, frosted-glass effect, minimalist typography, and a full-width mega menu for “Solutions.” The hero content subtly blurs and fades when the menu is hovered to keep focus on navigation.

## Highlights
- Frosted glass nav with `backdrop-blur` and low-opacity background
- Fixed top positioning with smooth, modern spacing
- Mega menu dropdown that spans the viewport
- Hover-driven focus effect on the page content
- Tailwind utility-first styling (no custom CSS required)

## How it works
- The nav is fixed at the top and styled to be semi-transparent.
- The “Solutions” item opens a full-width dropdown on hover.
- The page content uses peer-hover effects to blur and dim when the menu is active.

## Files
- [index.html](index.html)
- [tailwind.css](tailwind.css)

## Quick start
1. Open the HTML in a browser.
2. Hover over “Solutions” to see the mega menu.
3. Scroll the page to confirm the fixed nav behavior.

## Customization
- Replace the logo text with an image or SVG.
- Update menu labels and descriptions in the dropdown grid.
- Adjust spacing and opacity by changing Tailwind classes on the nav.
- Swap the hero image in the `images` folder with your own.

## Notes
- The dropdown is hover-based and intended for desktop interaction.
- For production, you may want to add focus handling and mobile behavior.

## License
MIT
