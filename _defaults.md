# Useful CSS Defaults

**All elements**

```css
*,
*::before,
*::after {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  border: none;
  color: inherit;
  font: inherit;
}
```

**body**

```css
body {
  font-family: var(--font, var(--font-fallback));
  font-size: 100%;
  line-height: 1.5; /* may need to be adjusted depending on font family */

  color: var(--c-bg);

  background: var(--c-bg);
  transition: background 0.1s ease-in-out; /* For dark / light theme transition  */
}
```

**text selection**

```css
::-moz-selection {
  color: var(--clr-1-c);
  background: var(--clr-1);
}
::selection {
  color: var(--clr-1-c);
  background: var(--clr-1);
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

**lists**

```css
ol,
ul {
  list-style: none;
}
```

**tables**

```css
table {
  border-collapse: collapse;
  border-spacing: 0;
}
```
