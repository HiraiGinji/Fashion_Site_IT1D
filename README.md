# TokyoFuku: Japanese Street Fashion Site

> A multi-page fashion website about Tokyo street style, covering outfits, style galleries, color and fit guides, editorial news, and designers.

---

## About

TokyoFuku ("Tokyo clothes") is an IT1D course project that showcases Japanese fashion culture. Visitors can browse outfit categories, explore style galleries such as Street Kei, Visual Kei, and Lolita, learn about color combinations and body-type styling, and read editorial articles.

## Features

- **Outfit categories**: Dresses, Clothes, Jeans, Shoes, Bags, and Accessories
- **Style gallery**: Street Kei, Visual Kei, and Lolita sections
- **Fit & Styles guides**: color combinations and physique-based styling tips
- **News / Editorial**: a news index with multiple article pages
- **Designers & References**: designer profiles and source references
- **Dropdown navigation**: multi-level menu with an auto-hiding header that slides away as you scroll down and returns as you scroll up
- **Custom typography**: Adlery Pro font plus Google Fonts (Pacifico, Inter, Noto Sans, Roboto)
- **Social icons**: Facebook and YouTube links via Font Awesome

## Site Map

| Section        | Pages                                                                                          |
| -------------- | ---------------------------------------------------------------------------------------------- |
| Home           | `index.html`                                                                                   |
| Outfits        | `dresses.html`, `clothes.html`, `jeans.html`, `shoes.html`, `bags.html`, `accessories.html`    |
| Gallery        | `gallery.html` (Street Kei, Visual Kei, Lolita)                                                |
| Fit & Styles   | `combination.html` (Color Combo), `physique.html`                                              |
| News           | `news.html`, `news1.html` to `news5.html`                                                      |
| Designers      | `designers.html`, `references.html`                                                            |

## Tech Stack

- HTML5, CSS3, and vanilla JavaScript
- [Font Awesome 6.7.2](https://fontawesome.com/) (via CDN)
- [Google Fonts](https://fonts.google.com/): Pacifico, Inter, Noto Sans, Roboto
- Custom font: Adlery Pro (`fonts/Adlery Pro/`)

## Project Structure

```
Fashion_Site_IT1D/
├── index.html            # Home page
├── dresses.html          # Outfit pages
├── clothes.html
├── jeans.html
├── shoes.html
├── bags.html
├── accessories.html
├── gallery.html          # Style gallery
├── combination.html      # Color combinations
├── physique.html         # Body-type styling
├── news.html             # News index
├── news1.html ... news5.html
├── designers.html
├── references.html
├── style.css             # Main stylesheet
├── styles1.css           # Additional styles
├── fonts/Adlery Pro/     # Custom font files
├── images/               # Site images
└── README.md
```

## Getting Started

No build step is required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/HiraiGinji/Fashion_Site_IT1D.git
   cd Fashion_Site_IT1D
   ```

2. **Open the site**
   - Double-click `index.html`, **or**
   - Serve it locally:
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000`.

> An internet connection is needed for Google Fonts and Font Awesome.
