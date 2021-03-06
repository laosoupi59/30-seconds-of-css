### Centering Grid

Horizontally and vertically centers a child element within a parent element using `grid`.

#### HTML

```html
<div class="centering-grid"><div class="child">Centered content.</div></div>
```

#### CSS

```css
.centering-grid {
  display: grid;
  justify-content: center;
  align-items: center;
  height: 100px;
}
```

#### Demo

#### Explanation

1. `display: grid` enables grid.
2. `justify-content: center` centers the child horizontally.
3. `align-items: center` centers the child vertically.

#### Browser support

- https://caniuse.com/#feat=css-grid

<!-- tags: layout -->
