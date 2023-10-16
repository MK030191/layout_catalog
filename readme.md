# Frontend practice with catalog page

Create HTML page with catalog. Develop semantic page structure as shown on [the mockup](https://www.figma.com/file/ojkArVazq7vsX0nbpn9CxZ/Moyo-%2F-Catalog-(ENG)?node-id=32249%3A354).

- Write styles in `src/styles/main.scss` instead of `src/style.css`
- use `Card` and `Header` blocks from previous tasks but rewrite them using BEM
and SCSS
- Nav links color is not `black` any more
- **flex layout**: there should always be 4 cards in a row (not 2, 3 or 5)
  - use `:nth-child(4n)` to select every 4th element in `flex` container
  - use `:nth-last-child(-n + 4)` to select 4 last elements `flex` container
- ❗️❗️❗️ **MANDATORY if you're familiar with the `grid`**
  - use `grid` instead of `flex`
  - implement the [Grid Layout instead](./grid.md)
- the distance between cards on the design includes borders (zoom in to see it);
- cards should have fixed width and fixed distances between them
- cards container should have fixed paddings (see 1024px example), bottom the same as top
- use semantic tags. `<header>`, `<nav>`, `<main>`
- add class `is-active` to the first link (`Apple`) in navigation
- remove old `data-qa` attributes
- add `data-qa="nav-hover"` (not just `hover`) to the 4th nav link for testing (`Laptops & computers`)
- add `data-qa="card"` to the first card
- add `data-qa="card-hover"` (not just `hover`) to the link `Buy` inside the first card

> Here are the [Layout Tasks Instructions](https://mate-academy.github.io/layout_task-guideline)

![screenshot](./reference.png)

## Checklist

❗️ Replace `<your_account>` with your Github username and copy the links to `Pull Request` description:
- [DEMO LINK](https://<your_account>.github.io/layout_catalog/)
- [TEST REPORT LINK](https://<your_account>.github.io/layout_catalog/report/html_report/)

❗️ Copy this `Checklist` to the `Pull Request` description after links, and put `- [x]` before each point after you checked it.

- [ ] Container's max-width calculated dynamically
- [ ] There are 4 cards in the row regardless of the window size
- [ ] SASS loop used to implement stars block
- [ ] Changing stars modifier in the code element reflects in
changing amount of active stars
- [ ] All `Typical Mistakes` from `BEM` lesson theory are checked.
- [ ] Code follows all the [Code Style Rules ❗️](https://mate-academy.github.io/layout_task-guideline/html-css-code-style-rules)
