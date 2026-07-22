# 08: Article

Write the CSS in `style.css`. The HTML is a small editorial article page. Match `goal.png`.

The point of this one is laying out a page to read well, which is mostly two things:

- **A centered column at a readable width.** Give `.post` a `max-width` around `60ch` (what is this unit?) and center the entire thing. Long lines are the most common thing that makes a page hard to read.
- **Rows that split left and right.** The `.byline` (author and date) and the `.post-foot` are each a flex row with `justify-content: space-between`.

Properties: `max-width`, `margin`, `display: flex`, `justify-content: space-between`.
