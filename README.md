# SVG

Learning Path for you:

- Practice basic shapes (line, circle, rect, polygon, text).
- Learn styling with CSS.
- Try small animations.
- Manipulate with JavaScript.
- Explore advanced topics: gradients, filters, paths (<path> is the most powerful).

🔹 <line> Element in SVG:

- A line is a simple shape defined by two points.

1. Core Line Attributes

| Attribute | Description                            |
| --------- | -------------------------------------- |
| `x1`      | The x-coordinate of the starting point |
| `y1`      | The y-coordinate of the starting point |
| `x2`      | The x-coordinate of the ending point   |
| `y2`      | The y-coordinate of the ending point   |

2. Presentation / Styling Attributes

These are used to control the appearance of the line:

| Attribute           | Description                                                                      | Example                              |
| ------------------- | -------------------------------------------------------------------------------- | ------------------------------------ |
| `stroke`            | Line color                                                                       | `stroke="red"`                       |
| `stroke-width`      | Thickness of line                                                                | `stroke-width="4"`                   |
| `stroke-linecap`    | Shape of line ends (`butt`, `round`, `square`)                                   | `stroke-linecap="round"`             |
| `stroke-opacity`    | Transparency of the stroke (0 → 1)                                               | `stroke-opacity="0.5"`               |
| `stroke-dasharray`  | Dashes/gaps pattern                                                              | `stroke-dasharray="5,3"`             |
| `stroke-dashoffset` | Where dash pattern starts                                                        | `stroke-dashoffset="2"`              |
| `opacity`           | Transparency of whole element                                                    | `opacity="0.7"`                      |
| `vector-effect`     | Controls scaling (`non-scaling-stroke` keeps stroke width constant when zooming) | `vector-effect="non-scaling-stroke"` |

3. Global Attributes (work on any SVG element)

| Attribute    | Description                                                    |
| ------------ | -------------------------------------------------------------- |
| `id`         | Unique identifier                                              |
| `class`      | Assign a CSS class                                             |
| `style`      | Inline CSS styles                                              |
| `transform`  | Apply transformations (`translate`, `rotate`, `scale`, `skew`) |
| `visibility` | Show or hide (`visible`, `hidden`)                             |
| `tabindex`   | Keyboard focus order (useful for accessibility)                |
