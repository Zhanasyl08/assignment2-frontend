# Defense Notes - Assignment 2

Use these notes to prepare for the practice lesson. Explain in your own words.

## 1. What is Flexbox?

Flexbox is a CSS layout model mainly used to arrange elements in one direction: row or column.

Important properties:
- display: flex
- flex-direction
- justify-content
- align-items
- gap
- flex

Example from my project:
.card-row {
    display: flex;
    gap: 22px;
    align-items: stretch;
}

## 2. What does justify-content do?

It controls alignment along the main axis.

Examples:
- flex-start
- center
- space-between
- space-around
- space-evenly

In my navigation:
justify-content: space-between;
This puts the logo on the left and links on the right.

## 3. What does align-items do?

It controls alignment on the cross axis.

In my header:
align-items: center;
This vertically centers the logo and navigation links.

## 4. Why are the cards equal height?

The parent `.card-row` is a flex container and the cards stretch to the same row height.
Inside every card I also use flex-direction: column.
The button has margin-top: auto, so it stays near the bottom.

## 5. What is CSS Grid?

CSS Grid is a layout system for rows and columns. It is useful for two-dimensional layouts.

Important properties:
- display: grid
- grid-template-columns
- grid-template-rows
- gap
- grid-template-areas
- grid-area

## 6. Explain Task 2 grid areas

The layout has:
grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";

The header and footer take both columns.
The sidebar is on the left and main content is on the right.

## 7. How is the gallery made?

.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
}

repeat(3, 1fr) means three equal columns.

## 8. How does the gallery hover work?

The caption is positioned at the bottom but starts outside the visible area.
On hover, `bottom: 0` moves it up.

The image also uses:
transform: scale(1.04);

## 9. Where are Flexbox and Grid combined in Task 4?

- Header: Flexbox
- Main portfolio area: CSS Grid
- Each project card: Flexbox
- Footer: full width after the main content

## 10. Flexbox vs Grid

Flexbox:
- mostly one direction
- good for navbars, rows, alignment inside components

Grid:
- rows and columns together
- good for full page layouts and galleries

## 11. What is gap?

`gap` creates equal space between flex or grid items without adding separate margins to every element.

## 12. What is 1fr?

`fr` means a fraction of the available grid space.

Example:
grid-template-columns: 2fr 1fr;
The left column gets about two parts and the right column gets one part.

## 13. Possible live coding changes

Be ready to do these in class:
- change `gap: 22px` to another value
- change `justify-content`
- change card direction from row to column
- change gallery from 3 columns to 4 columns
- change `grid-template-columns: 230px 1fr`
- move sidebar/main positions in grid areas
- add or remove a hover effect
- fix a missing `display: flex` or `display: grid`
