# Niksalehi Clone

A static front-end clone of the [Niksalehi](https://www.niksalehi.com) news website, built with plain HTML and CSS.

![HTML](https://img.shields.io/badge/HTML-63.5%25-e34c26)
![CSS](https://img.shields.io/badge/CSS-36.5%25-264de4)
![License](https://img.shields.io/badge/license-MIT-green)

## Overview

This project recreates the layout and visual style of the Niksalehi homepage — a Persian news portal — using only static HTML and CSS. It's a good reference for practicing real-world layout techniques: multi-column news grids, tab-based content switching, and RTL (right-to-left) typography.

## Features

- **Navigation bar** — top blue bar with logo, search icon, and title bar
- **Main picture news** — hero section for featured/highlighted stories
- **Old content sections** — repeated article blocks with thumbnails and titles
- **Tab box** — a tabbed widget for switching between content views
- **Box Omen** — a dedicated section for special/featured content
- **A Review of the Past** — a "flashback" section for historical content
- **Image galleries** — thumbnail lists/grids for article previews
- **Footer** — copyright and site info

## Project Structure

```
niksalehi/
├── css/         # Stylesheets for layout, typography, and components
├── fonts/       # Custom/Persian web fonts used across the site
├── images/      # Image assets (icons, thumbnails, banners)
├── index.html   # Main entry point of the site
└── README.md
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- No build tools, package managers, or server required

### Run locally

```bash
# Clone the repository
git clone https://github.com/mohammad154/niksalehi.git

# Navigate into the project
cd niksalehi

# Open index.html in your browser
```

On most systems you can simply double-click `index.html`, or serve it locally:

```bash
# Python 3
python -m http.server 8000
# then visit http://localhost:8000
```

## Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m "Add my feature"`)
4. Push to your branch (`git push origin feature/my-feature`)
5. Open a pull request against `master`

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE.md) file for details.

## Disclaimer

This is an independent, unofficial clone created for educational/practice purposes. It is not affiliated with or endorsed by Niksalehi.
