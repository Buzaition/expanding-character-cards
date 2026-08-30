# Expanding Character Cards

A polished front-end interaction featuring two Spider-Man character cards that expand on hover, reveal character artwork, and animate into view on scroll.

The project is intentionally lightweight: **HTML + CSS + AOS** with no framework required.

## Preview

- Classic red Spider-Man card
- Black-suit Spider-Man card
- Expanding circular color reveal
- Rotating spider emblems
- Character artwork reveal on hover
- Reversed horizontal gradient background from light red to black
- Responsive layout for desktop and mobile
- AOS-powered entrance animations

## Tech Stack

- HTML5
- CSS3
- AOS — Animate On Scroll

## Project Structure

```text
expanding-character-cards/
├── images/
│   ├── spider-red-logo.png
│   ├── spider-black-logo.png
│   ├── spiderman-red.png
│   └── spiderman-black.png
├── index.html
├── animation.css
└── README.md
```

## Run Locally

Clone the repository:

```bash
git clone https://github.com/Buzaition/expanding-character-cards.git
cd expanding-character-cards
```

Then open `index.html` in your browser.

For the smoothest local-development workflow, you can also serve the folder with any simple static server such as VS Code Live Server.

## Customization

Each card uses a CSS custom property for its primary reveal color:

```html
<div class="superhero-circle" style="--hero_clr:#f40103">
```

Change `--hero_clr`, replace the logo and character PNGs, and update the card copy to reuse the component for another character.

The page background is defined in `animation.css`:

```css
background: linear-gradient(270deg, #f7a3a3 0%, #d96b6b 28%, #242424 68%, #050505 100%);
```

## Assets

The repository includes individually separated transparent-background PNG assets for both character artworks and both spider emblems so they can be reused independently in the card animation.

## Author

Developed by **Abuzaid Saad**.

GitHub: [@Buzaition](https://github.com/Buzaition)

## License

This repository is intended as a front-end animation/demo project. Character names and related superhero imagery remain the property of their respective rights holders.
