# Travel Destination Showcase (For India)

A static, responsive travel showcase web page highlighting six destinations across India, built entirely with **pure HTML5 and CSS3**—with zero JavaScript, frameworks, or build tools. Created as a **Semester 1 Group Project**.

## Features

- **Six Indian Destination Cards:** Highlights **Coorg (Karnataka)**, **Spiti (Himachal Pradesh)**, **Cherapunji (Meghalaya)**, **Darjeeling (West Bengal)**, **Gulmarg (Jammu & Kashmir)**, and **Ladakh (India)** using semantic `<article>`, `<figure>`, and `<figcaption>` elements with photography sourced from Unsplash.
- **Pure CSS Season Filtering:** Filter destinations by `All Seasons`, `Spring`, `Summer`, `Autumn`, `Winter`, or `Monsoon` using hidden `<input type="radio" name="season-filter">` controls paired with CSS `:checked` sibling combinators.
- **Pure CSS Favorite Toggle:** Interactive heart toggle on each card powered by a hidden `<input type="checkbox" class="fav-checkbox">` element.
- **Color-Coded Season Tags:** Distinct visual badges for each season (`.tag-spring`, `.tag-summer`, `.tag-autumn`, `.tag-winter`, `.tag-monsoon`).
- **Destination Comparison Guide:** A horizontally scrollable comparison table (`.table-responsive`) detailing each destination's best season, average daily cost in INR (`4k–5k / day` or `5k–6k / day`), top highlight, and visitor rating (`4.8 / 5.0` to `5.0 / 5.0`).
- **Responsive Grid Layout:** Adapts seamlessly across screen sizes using CSS Grid and media queries:
  - **Desktop (`> 992px`):** 3-column card grid
  - **Tablet (`<= 992px`):** 2-column card grid
  - **Mobile (`<= 640px`):** 1-column card grid

## Tech Stack

| Technology | Share | Usage |
| :--- | :---: | :--- |
| **HTML5** | 62.1% | Semantic page structure, radio/checkbox filter and favorite inputs, destination cards, and comparison table |
| **CSS3** | 37.9% | `:root` custom properties, CSS Grid, Flexbox, `:checked` sibling selectors, color-coded tags, and responsive `@media` queries |

No JavaScript, third-party libraries, or package managers are required.

## Project Structure

```text
Travel-Destination-Showcase/
├── README.md     # Project documentation
├── index.html    # Main markup: header, season filters, 6 destination cards, comparison table, and footer
└── style.css     # Complete styling, CSS variables, interactive states, and responsive breakpoints
```

Key source files on GitHub:
- [`index.html`](https://github.com/Diptkumar/Travel-Destination-Showcase/blob/main/index.html)
- [`style.css`](https://github.com/Diptkumar/Travel-Destination-Showcase/blob/main/style.css)

## Getting Started

Because this project uses only static HTML and CSS, no installation or build step is needed.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Diptkumar/Travel-Destination-Showcase.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Travel-Destination-Showcase
   ```
3. **Open in your browser:**
   - Double-click `index.html`, or
   - Open it with a local development server (such as VS Code's Live Server extension).

> **Note:** An active internet connection is required to load the destination photographs hosted on Unsplash (`images.unsplash.com`).

## Contributors

- **Diptkumar** (`@Diptkumar`)
- **Vivek Yadav** (`@vivekyadav123456`)
- **DHANNJAY GUPTA** (`@Dhannjay-su21`)

## Repository & License

- **Repository:** [Diptkumar/Travel-Destination-Showcase](https://github.com/Diptkumar/Travel-Destination-Showcase)
- **License:** No license is currently specified in this repository. Add a `LICENSE` file if you plan to distribute or accept external contributions.
