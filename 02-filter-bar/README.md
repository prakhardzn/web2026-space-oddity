# 02: Filter bar

Fix the CSS in `style.css`. Do not change the HTML.

The filter buttons should wrap onto new lines when the row runs out of width, with an even gap between them. Right now they squash into a single line instead of wrapping, and they have no gap.

Two things are wrong:

- `flex-wrap` is set to `nowrap`.
- There is no `gap`.

Fix both, then drag the window narrow and watch the buttons reflow onto new lines. `gap` applies to both the rows and the columns.

Properties: `flex-wrap`, `gap`.
