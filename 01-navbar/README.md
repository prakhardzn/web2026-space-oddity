# 01: Navbar

Fix the CSS in `style.css`. Do not change the HTML.

The logo should sit on the left, the three links on the right, all on one row and vertically centered, with a gap between the links.

Four things are wrong:

- `.navbar` is not a flex container.
- The logo and links are not pushed to opposite ends.
- They are not vertically centered.
- `.links` has a `gap` but the links are still stacked, because `gap` does nothing until the element is a flex container too.

Properties: `display`, `justify-content`, `align-items`, `gap`.
