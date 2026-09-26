File Organization
`index.html`: Contains 6 box elements (A through F) inside a main container.
`styleA.css`: Styles the page vertically with centered, evenly spaced boxes.
`styleB.css`: Styles boxes A-E horizontally at the top-left and fixes box F to the bottom-right corner.
`README.md`: Explains the repository structure and challenges faced during the project.

Challenges Faced
Vertical Spacing in Style A: Setting up Flexbox with `justify-content: space-between` so the vertical gaps between boxes expand evenly on screen resize without changing the 100x100px box size.
Positioning Box F in Style B: Keeping boxes A-E in a horizontal line while detaching box F to stay permanently fixed at the bottom-right corner using `position: fixed`.
