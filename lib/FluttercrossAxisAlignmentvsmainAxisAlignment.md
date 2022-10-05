# Flutter crossAxisAlignment vs mainAxisAlignment

## For Row:

`mainAxisAlignment` = Horizontal Axis

`crossAxisAlignment` = Vertical Axis

## For Column:

`mainAxisAlignment` = Vertical Axis

`crossAxisAlignment` = Horizontal Axis

These two pictures are clear to show the meaning of MainAxisAlignment and CrossAxisAlignment.

When you use a `Row`, its children are laid out in a row, which is horizontally. So a Row's main axis is horizontal.
Using `mainAxisAlignment` in a Row lets you align the row's children horizontally (e.g. left, right).
The cross axis to a Row's main axis is vertical. So using `crossAxisAlignment` in a Row lets you define,
how its children are aligned vertically.

In a `Column`, it's the opposite. The children of a column are laid out vertically, from top to bottom (per default).
So its main axis is vertical. This means, using `mainAxisAlignment` in a Column aligns its children vertically (e.g. top, bottom)
and `crossAxisAlignment` defines how the children are aligned horizontally in that Column.

## Row/Column are associated to an axis:

- Horizontal for `Row`
- Vertical for `Column`

`mainAxisAlignment` is how items are aligned on that axis. `crossAxisAlignment` is how items are aligned on the other axis.
