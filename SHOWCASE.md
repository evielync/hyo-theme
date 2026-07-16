# Hyo — a warm, earthy theme

A calm writing surface: white editor, parchment sidebar, and a soft **peach accent** that carries links, tags, and highlights without ever shouting. This note shows every element the theme styles — open it in Hyo and it doubles as the showcase.

Text can be **bold**, *italic*, ~~struck through~~, ==highlighted==, or set as `inline code`. Links glow in the accent — see [evchapman.com](https://evchapman.com) or an internal [[Another Note|linked note]]. Tags sit in soft peach pills: #theme #obsidian #hyo.

## Typography sets the tone

### Third-level heading
#### Fourth-level heading

Body copy stays warm and readable at a comfortable measure. The palette leans into earthy neutrals so nothing competes with your words — the accent appears only where it earns attention.

> A blockquote holds a borrowed thought.
> The left border picks up the accent, and the text softens just enough to read as *quoted*.

## Callouts carry the accent

> [!note]
> The default callout tints itself peach — headers, icon, and a faint wash behind the text.

> [!tip] A titled tip
> Callouts inherit the warm system, so a whole stack of them reads as one family.

> [!warning]
> Warnings shift to a warmer amber while staying inside the palette.

## Lists, nested and checked

- Top-level point
  - A nested detail
    - And one level deeper
- Back to the top level

1. First step
2. Second step
3. Third step

- [ ] An open task
- [x] A completed task
- [ ] Another thing to do

## Code, with syntax colour

Inline `const accent = "#D97757"` sits quietly in the flow. Fenced blocks get full syntax colouring:

```js
// Keywords, strings, and functions each take their own tone
function applyAccent(el) {
  const accent = "#D97757";       // peach
  el.style.setProperty("--color-accent", accent);
  return `Hyo applied ${accent}`;
}

applyAccent(document.body);
```

## Tables stay tidy

| Element   | Colour      | Role                     |
| --------- | ----------- | ------------------------ |
| Accent    | `#D97757`   | Links, tags, highlights  |
| Editor    | White       | The writing surface      |
| Sidebar   | Parchment   | Calm, low-contrast frame |
| Text      | Warm charcoal | Comfortable reading     |

---

Everything above uses one small system: a warm neutral base, and a single peach accent applied with restraint. That's Hyo.
