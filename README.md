# Sharpening my FlexBox skills
- [Wes Bos vid](https://flexbox.io/)

## Built With
- HTML5, CSS3 and normalize.css

## Getting started
- $ yarn/npm install
- $ open index.html in browser

## Acknowledments
[Wes Bes](http://wesbos.com/), [Abbey Fitzgerald](https://github.com/abbeyjfitzgerald)

## Notes
  - `flex-direction: row` is default.
  - Main axis: `flex-direction: row` is from left to right, Cross axis is from top to bottom.
  - Main axis: `flex-direction: column` is from top to bottom, Cross axis is from left to right.
  - Main axis: `flex-direction: row-reverse` is from right to left, Cross axis is from bottom to top.
  - Main axis: `flex-direction: column-reverse` is from bottom to top, Cross axis is from right to left.

  - Flex container is parent and flex item is child, i.e.,
    ```
    <div class="container">
      <p class="item"></p>
    </div>
    ```
  - flex-wrap (default is `flex-wrap:nowrap`): `flex-wrap:wrap` on parent 

### Order on flex item
  - example: `order: 5;`
  - default order for anything not set is 0,  so any value above zero will go to end and start count there. 
  can overwrite default value: `order: 1` on all items.
  - negative values work as well.

### Flexbox Alignment and Centering with `justify-content`
  - How are the items aligned on the main-axis?
  - flex-start is default
  - flex-start, flex-end, center, space-between, space-around.

### `align-items` (more concerned with cross-axis)
  - aligns items inside a flex container along the cross axis just like `justify-content` does along the main axis. 
  - default is `align-items: stretch`

### `align-content`
  - `align-content` is for multi line flexible boxes. It has no effect when items are in a single line. It aligns the whole structure according to its value.

### align-self
  - target individual element to override parent setting. ex: `align-self: center`



 
