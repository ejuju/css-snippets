# Useful CSS Defaults

**All elements**

```css
*,
*::before,
*::after {
  box-sizing: border-box;
  padding: 0;
  margin: 0;

  color: inherit;
  font: inherit;
}
```

**body**

```css
body {
  background: var(--c-bg);
  transition: background 0.1s ease-in-out;
  color: var(--c-bg);
  font-family: var(--font, var(--font-system));
  line-height: 1.5; /* may need to be adjusted depending on font family */
}
```

**headings**

```css
h1,
h2,
h3 {
  line-height: 1.25;
}
h1 {
  font-weight: var(--fw-bold);
  font-size: var(--fs-h1);
}
h2 {
  font-weight: var(--fw-bold);
  font-size: var(--fs-h2);
}
h3 {
  font-weight: var(--fw-bold);
  font-size: var(--fs-h3);
}
```

**links**

```css
a {
  text-decoration: underline;
}
```

**buttons**

```css
button {
  background: none;
  border: none;
  width: max-content;
  text-align: left;
  cursor: pointer;
  font-weight: inherit;
}
```
