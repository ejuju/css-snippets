# Spacing

```css
:root {
  --s-pagetop: 2rem;
  --s-pagebottom: 6rem;
  --s-sides: 1rem;
  --s-page: var(--s-pagetop) var(--s-sides) var(--s-pagebottom);

  @media (min-width: 1000px;) {
    --s-sides: 3rem;
    /* --s-sides: calc(1rem + 5vw); */
  }
}
```
