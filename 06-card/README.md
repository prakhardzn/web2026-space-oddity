# 06: Card

Build both the HTML and the CSS from scratch, to match `goal.png`.

Work in this order:

1. Look at `goal.png` and mark the boxes. There is a header row with two sides (avatar and name on the left, a button on the right), and below it a row of three stats.
2. Write the HTML for those boxes.
3. Style them. The header is a flex row with `justify-content: space-between` and `align-items: center`. The stats are a flex row of three equal columns, and each column is itself a small flex column (number over label).

A row that contains columns means a flex container whose children are themselves flex containers set to `flex-direction: column`. That nesting is the main idea here.