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

### Main Pages
- [index.html](index.html) – Home page with hero section
- [about.html](about.html) – About page template

### Solutions Submenu Pages
- [performance.html](performance.html) – Performance solutions template
- [automation.html](automation.html) – Automation solutions template
- [agentic.html](agentic.html) – AI/Agentic solutions template
- [innovation.html](innovation.html) – Innovation solutions template

### Assets
- [tailwind.css](tailwind.css)
- `images/` – Hero and asset images

## Quick start
1. Open `index.html` in a browser.
2. Hover over "Solutions" to see the mega menu.
3. Click any submenu item to navigate to its template page.
4. Scroll the page to confirm the fixed nav behavior.

## Structure
Each page includes:
- Reusable frosted-glass nav bar with working dropdown
- Peer-hover blur effect on content when menu is open
- Placeholder content cards ready for customization
- Active page highlighting in the dropdown

## Customization
- Replace the logo text with an image or SVG.
- Update menu labels, descriptions, and links in the dropdown grid.
- Adjust spacing and opacity by changing Tailwind classes on the nav.
- Swap the hero image in the `images` folder with your own.
- Edit the content cards on each submenu page to match your services.

## Notes
- The dropdown is hover-based and intended for desktop interaction.
- For production, you may want to add focus handling and mobile behavior.
- The nav component is duplicated across pages; consider extracting to a shared include for larger projects.

## License
MIT
