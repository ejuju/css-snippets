# Util

## Buttons

Various states should be taken into account:

- Disabled (ex: form input is not valid)
- Waiting (ex: awaiting server response)

Also, various styles should be available using classes:

- Filled (default: filled with primary brand color)
- Outline (outline but not filled)
- Link (looks like a link)

```scss
.btn {
  cursor: pointer;
  padding: 0.5rem 1rem;
  display: flex;

  font-weight: var(--fw-bold);
  text-decoration: none;
  text-align: left;

  border-radius: var(--br);
  box-shadow: inset 0 0 0 var(--bw) currentColor;

  &.link {
    box-shadow: none;
    padding: 0;
    text-decoration: underline;
  }

  &.c-1 {
    background: var(--clr-1);
    transition: background 0.2s ease-in-out;
    color: var(--clr-1-c);
    box-shadow: none;
  }

  &:disabled {
    cursor: not-allowed;
    opacity: 0.9;
    background: var(--clr-bg-2);
  }

  &.waiting {
    cursor: wait;
    background: var(--clr-bg-2);
  }
}
```
