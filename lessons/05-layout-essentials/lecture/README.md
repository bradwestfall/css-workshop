# Lecture

- Normal Flow
- Absolute Position
  - Centering
- Transforms
  - Centering
- Aspect Ratios
- Media Queries
- Container Queries

## Examples

1. Build a form input that uses absolute positioned icon (like a search input) and then `:focus-within` to manage the focus look

2. Build a layout using `position: absolute` for a fixed header and footer. Make the content in the middle span the distance between the header and footer and show the issues that arise when we use an absolute positioning strategy.

3. Demonstrate various centering needs and the different ways to center

- `margin: 0 auto`
- `margin: auto`
- Absolute positioning and transforms to center (unknown width)
- Negative margins (known width lightboxes)

Let's try to center a block level thing with `margin: auto`. Notice we have to give it a width of something in order for it to take the centering effect. Historically this is true but now we can do `width: max-content`:

https://developer.mozilla.org/en-US/docs/Web/CSS/max-content
https://codepen.io/matuzo/pen/GRrGWRz

With absolute-positioned items, we can center them with `margin: auto` only if we set a `width` and `height` and also a top/right/bottom/left like this:
https://codepen.io/bradwestfall/pen/MWwdQpY
