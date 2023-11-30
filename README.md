# CSS Grid simplified

- [CSS Grid simplified course by Shruti Balasa](https://laracasts.com/series/css-grids-simplified)
- [Based of the original source code](https://github.com/laracasts/css-grids-simplified)

## Table of Contents

- [01 First look at CSS Grid](https://dragoncillos.github.io/CSS-Grid/01-first-look.html) *grid-template-columns*
- [02 Sizing cells](https://dragoncillos.github.io/CSS-Grid/02-sizing-cells.html) *grid-template-columns: 1fr 2fr*
  - [02b Fast food menu](https://dragoncillos.github.io/CSS-Grid/02b-fast-food-menu.html) Fast food menu: *grid-template-columns: 1fr auto*
- [03 Creating Rows](https://dragoncillos.github.io/CSS-Grid/03-page-layout-grid.html) Page layout grid: *grid-template-rows: auto 1fr auto*
  - [03b Full page menu](https://dragoncillos.github.io/CSS-Grid/03b-full-page-menu.html) *grid-template: repeat(2, 1fr) / repeat(3, 1fr)*
- [04 Spacing between cells](https://dragoncillos.github.io/CSS-Grid/04-spacing-between-cells.html) Fast food menu: *column-gap: 2rem -> row-gap: 2rem -> gap: 2rem 2rem -> gap: 2rem;*
  - [04b Shopping cart summary](https://dragoncillos.github.io/CSS-Grid/04b-shopping-cart-summary.html) Shopping Cart Summary *justify-content, align-content* -> shorthand *place-content: align-content justify-content*
- [05 Horizontal and Vertical Spacing](https://dragoncillos.github.io/CSS-Grid/05-team-profiles.html) Team profiles:
  - *justify-content vs justify-items*
  - *shorthand place-items: align-items justify-items*
  - *align-items*
  - [05b Center div](https://dragoncillos.github.io/CSS-Grid/05b-center-div.html) *place-items: center center = place-items: center*
- [06 Single Cell Alignment](https://dragoncillos.github.io/CSS-Grid/06-restaurant-ratings.html) Restaurant ratings: *align-self, justify-self*
  - [06b Profile card](https://dragoncillos.github.io/CSS-Grid/06b-profile-card.html):
    - Shorthand *place-content: align-content justify-content*
    - CSS properties that could be used on individual items of a grid: *align-self and justify-self*
- [07 Merge and Swap Cells](https://dragoncillos.github.io/CSS-Grid/07-contact-form.html) Contact form:
  - grid-column-start: 2 == grid-column: 2;
  - grid-row-start: 1; grid-row-end: 3 == grid-row: 1 / 3;
  - grid-area: 1 / 2 / 3;
  - grid-column: span 2;
		  
