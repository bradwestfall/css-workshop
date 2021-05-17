# 2. Selectors and Cascade

- Basic Selectors
  - type, id, class, attribute
- Selector Combinators
  - [space] Descendants
  - `>` Direct Descendant
  - `+` Adjacent Sibling
  - `~` Sibling
- Pseudo-Selectors
  - `:focus`
  - `:hover`
  - `:first-child`
  - `:last-child`
  - `:nth-child`
  - `:nth-child(odd/even)`
  - `:not()`
- Basic Selector Strategy
- Specificity
- Cascade

## Cascade Order of Importance

Lowest to highest:

### Initial & Inherited Properties (default values)

The lowest weight are the values the browser gives an element through defaults or inheritance

### Ruleset Order of Appearance

If two rulesets target the same element, the second one will win (assuming they have the same specificity)

### Selector Specificity

If two rulesets target the same element but one has more specificity, the one that is more specific wins

### Inline Styles

If the element has inline styles, those will win over above of the above circumstances.

### Importance

If a rule has `!important` on it, then it will win

## Specificity Calculator

https://specificity.keegan.st
