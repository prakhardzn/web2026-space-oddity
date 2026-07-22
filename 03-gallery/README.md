# 03: Gallery

Write the CSS in `style.css`. The HTML is done. Match `goal.png`.

Two parts:

1. `.featured` fills the viewport height and holds one image centered across and down. This is the "center a div" problem, the most common layout question there is: a flex container with some `min-height`, `justify-content`, `align-items`.
2. `.thumbs` is a row of three images with an even gap that share the width. Try to give an even space around them, then try giving each figure `flex: 1` instead and notice the difference.

Also add `max-width: 100%` to the images so they stay inside their frames.

Properties: `justify-content`, `align-items`, `min-height`, `gap`, `flex`, `max-width`.
