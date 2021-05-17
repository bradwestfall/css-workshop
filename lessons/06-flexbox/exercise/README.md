# Exercise

This exercise is inspired by https://codepen.io/oliviale/full/WqwOzv

## Task: Build Three Cards

Tips

- Only change the HTML (add classes or elements) if instructed to
- Try to use `em` units as much as you can

Three Variations of Cards:

### Card 1

The instructor will do the first card for the group and also introduce some new concepts like:

- "vertical rhythm" with a `.spacing-util` utility (lobotomized owl)

### Card 2

- We're going to need to add another `div` somewhere to get this one to work. Plan with the instructor as to where to add the new `div`.
- Remember to build from the outside-in.
- You can use padding on the overall card and then "pull" the image out of that padding to the edge of the card with negative margins on the top, bottom, and left.
- The image will overflow the card a little in the corners since it has square corners and the card is rounded. Use `overflow: hidden` on the card to hide that overflow (and to give the image a round-corner look).
- When we do layout with flexbox to put things side-by-side, we usually want at least one item to be `flex: 1`. In our case it probably makes sense for the div we just added which serves as the middle of the card to be that thing since the image size and button size will grow their respective flex items. To select that div, you can do:

```css
img + div {
  flex: 1;
}
```

- You can probably copy the attributes css that we did in card 1 down and it will work just right
- Since the button is a flex-item, it will stretch to vertical height of the card, use `align-self: center` to change that default behavior.

### Card 3

- You'll probably find card 3 to be easy once you've done card 2. Only this time you'll have to add two new element containers. One for all the stuff above the line and one for all the stuff below.
- Maybe you could use `header` and `footer`?
