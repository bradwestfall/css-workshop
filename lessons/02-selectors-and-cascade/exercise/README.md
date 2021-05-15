# Exercise

## Task 1

To start, this is a selector "cheetsheet" game that tests your knowledge with selectors and combinators. Try it out!

https://frontend30.com/css-selectors-cheatsheet/

The article that goes with it:
https://medium.com/design-code-repository/css-selectors-cheatsheet-details-9593bc204e3f

# Task 2

See if you can write some selectors to select specific elements and make the background colors of these elements according to the instructions below:

1. Open `styles.scss` to make edits.
2. Open `final.png` to see what the final should look like.
3. DO NOT edit the HTML file to add classes or other attributes to make selection easier 😉. This is more about seeing if we _can_ select the things we want, not about writing the best HTML to make things easy to select.
4. Notice there is some CSS that attempts to make the dog's attributes `blue`. But it's not working. This is actually a specificity issue with the cascade. See if you can fix some other code (not the last selector for `.dog-attribute`) so the blue color will apply.
5. Select the "Share" link and make the `background-color: lime;`. Do it in a way such that if there were other `.dog` records on the page, their share link would also be selected. You might have to get clever because you can't use `:nth-child(2)` since that would also select the "Like" link in some cases where there is no "Share" link.
