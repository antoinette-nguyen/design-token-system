# Design Token System

A single source of truth for all visual design decisions — color, typography, spacing, shadows, and motion. Used across all projects in my 9-month portfolio build.

## What's inside

| Token category | File |
|----------------|------|
| Colors (neutral + accent + semantic) | `tokens.css` |
| Typography (scale, weight, leading, tracking) | `tokens.css` |
| Spacing (4px base, 13-step scale) | `tokens.css` |
| Border radius | `tokens.css` |
| Shadows | `tokens.css` |
| Motion (duration + easing) | `tokens.css` |
| Z-index | `tokens.css` |

## How to use

Import into any CSS file:

```css
@import url('https://raw.githubusercontent.com/antoinette-nguyen/design-token-system/main/tokens.css');
```

Or copy `tokens.css` into your project and import locally:

```css
@import url('./tokens.css');
```

Then use tokens anywhere in your CSS:

```css
.card {
  background: var(--color-surface);
  border-radius: var(--radius-lg);
  padding: var(--space-6);
  box-shadow: var(--shadow-md);
  transition: box-shadow var(--duration-base) var(--ease-out);
}
```

## Visual reference

Open `index.html` in your browser to see all tokens rendered as an interactive reference — click any color swatch to copy the CSS variable name.

---

*Part of a [9-month portfolio build](https://github.com/antoinette-nguyen) · Phase 1 · Month 1 · Week 3*
