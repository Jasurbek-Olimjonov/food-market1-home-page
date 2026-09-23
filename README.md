# Blog Post Page

A magazine-style page built as a front-end practice project, focused on translating a design into a pixel-close layout using Bootstrap's utility classes and SASS.

## Live Demo
[View live site](https://Jasurbek-Olimjonov.github.io/food-market1-home-page/)

## Overview
This project recreates a full home page layout — welcome section, categories, inbox to follow, recipe columns and instagram post part are built with Bootstrap's utilities (like `d-flex`, `carousel slide` and mostly `auto-fit` property of '`d-grid`), used SASS for staff Bootstrap couldn't handle.

## Approach
Most of the layout — spacing, alignment, and structure — was handled using Bootstrap's built-in utility classes (`d-flex`, `position-absolute`, margin/padding helpers, etc.) rather than writing custom CSS from scratch. Also used `carousel item` element built with Bootstrap's default utilities related to that and custom SASS was used selectively, for the specific layout details and fine adjustments that Bootstrap's utility system doesn't cover directly.

## What I Practiced
- Deciding when to reach for a utility class vs. writing custom SASS
- Positioning elements precisely within their containers using `flex`, `position`, and `translate-middle` utilities
- Using `auto-fit` property of grid box to make the content flexible
- Centering and aligning overlapping elements (like images and badges) using Bootstrap's `translate-middle` class combined with `position-absolute`

## Project Structure

```
food-market1-home-page/
├── assets/
|   ├── images/
|   ├── svg/
├── styles/
│   ├── sections/
│   ├── utils/
│   │   ├── _mixins.scss
│   │   ├── _utilities.scss
│   │   └── _variables.scss
│   ├── style.css
│   ├── style.css.map
│   └── style.scss
├── LICENSE
└── index.html
```

## Getting Started
Clone the repo and open `index.html` in your browser — or, if you're editing the SASS:
```bash
git clone https://github.com/Jasurbek-Olimjonov/food-market1-home-page.git
cd food-market1-home-page
# compile SASS if using a live-sass-compiler or similar
```

## Author
**Jasurbek Olimjonov**
[GitHub](https://github.com/Jasurbek-Olimjonov)

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
