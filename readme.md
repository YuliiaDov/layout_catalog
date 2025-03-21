# Frontend practice with catalog page
Replace `<your_account>` with your Github username and copy the links to Pull Request description:
- [DEMO LINK](https://<your_account>.github.io/layout_catalog/)
- [TEST REPORT LINK](https://<your_account>.github.io/layout_catalog/report/html_report/)

> Follow [this instructions](https://github.com/mate-academy/layout_task-guideline#how-to-solve-the-layout-tasks-on-github)
___
> Write styles in `src/styles/main.scss` instead of `src/style.css`.
___

## The task
Create HTML page with catalog. Develop semantic page structure as shown on [the mockup](https://www.figma.com/file/euXjY316CHKYkPRO1K0kjLsF/Moyo-Catalog?node-id=0%3A1).

## Requirements:
- use `Card` and `Header` blocks from previous tasks but rewrite them using BEM and SCSS
- Nav links color is not black any more
- page width is always >= 1024px
- there should always be 4 cards in a row (not 2, 3 or 5)
  - use `:nth-child(4n)` to select every 4th element
  - use `:nth-last-child(-n + 4)` to select 4 last elements
- cards should have fixed width and fixed distances between them
- cards container should have fixed paddings (see 1024px example), bottom the same as top
- use semantic tags. `<header>`, `<nav>`, `<main>`
- add class `is-active` to the first link (`Apple`) in navigation
- add attribute `data-qa="nav-hover"` (not just `hover`) to the 4th nav link for testing (`Ноутбуки и компьютеры`)
- add attribute `data-qa="card"` to the first card
- add attribute `data-qa="card-hover"` (not just `hover`) to the link `Купить` inside first card
---
--> [CHECKLIST](https://github.com/mate-academy/layout_catalog/blob/master/checklist.md)
---
![screenshot](./references/catalog-example.png)
