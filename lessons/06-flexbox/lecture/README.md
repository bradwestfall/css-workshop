# Lecture

- Flexbox
  - `flex-shrink`
  - `flex-grow`
  - `flex-basis`
  - `flex` shorthand
  - `flex-direction`
  - `gap` vs `margin`
- Centering
- Tiles

```css
.container {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.item {
  flex: 1 1 calc((100% / 3) - 2rem);
}
```

## Resources

https://mastery.games/post/the-difference-between-width-and-flex-basis/
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://flexbox.io/
https://tobiasahlin.com/blog/common-flexbox-patterns/
