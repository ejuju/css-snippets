# Colors

** Global variables **

```css
:root {
  /* BLACK AND WHITES */

  --c-black-0: hsl(0, 0%, 10%);
  --c-black-1: hsl(0, 0%, 12%);
  --c-black-2: hsl(0, 0%, 20%);

  --c-white-0: hsl(0, 0%, 100%);
  --c-white-1: hsl(0, 0%, 95%);
  --c-white-2: hsl(0, 0%, 85%);

  /* TRANSPARENT COLORS */

  --c-black-t: hsla(0, 0%, 0%, 0.75); /* same as above */
  --c-white-t: hsla(0, 0%, 100%, 0.75); /* Useful for image overlays */

  /* UI COLORS */

  --c-green-white: hsl(125, 100%, 60%);
  --c-green-black: hsl(125, 70%, 40%);

  --c-yellow-white: hsl(50, 100%, 60%);
  --c-yellow-black: hsl(50, 70%, 40%);

  --c-red-white: hsl(0, 100%, 60%);
  --c-red-black: hsl(0, 70%, 40%);

  /* BRAND */

  --c-1: hsl(125, 100%, 75%); /* primary color */
  --c-1-contrast: #000; /* Useful when using light / dark themes */
}
```

** Light theme **

```css
body.light {
  --c-txt: var(--c-black-0);
  --c-txt-1: var(--c-black-1);
  --c-txt-2: var(--c-black-2);

  --c-bg: var(--c-white-0);
  --c-bg-1: var(--c-white-1);
  --c-bg-2: var(--c-white-2);

  /* UI COLORS */
  --c-success: var(--c-black-green);
  --c-warning: var(--c-black-yellow);
  --c-error: var(--c-black-red);
}

body.dark {
  --c-txt: var(--c-white-0);
  --c-txt-1: var(--c-white-1);
  --c-txt-2: var(--c-white-2);

  --c-bg: var(--c-black-0);
  --c-bg-1: var(--c-black-1);
  --c-bg-2: var(--c-black-2);

  /* UI COLORS */
  --c-success: var(--c-white-green);
  --c-warning: var(--c-white-yellow);
  --c-error: var(--c-white-red);
}
```
