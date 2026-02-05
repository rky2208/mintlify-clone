```md
# Mintlify Landing Page Clone

A clean recreation of Mintlify's homepage using just HTML and CSS. No frameworks, no JavaScript—just the basics done well.

---

## Why This Project?

I wanted to practice building real-world layouts without relying on frameworks. This project helped me get better at:

- Writing semantic HTML
- Understanding Flexbox and Grid deeply
- Organizing CSS so it doesn't become a mess
- Building pixel-perfect designs from scratch

---

## What's Inside

**Tech:**

- HTML5
- CSS3 (Flexbox, Grid)
- Custom fonts (Inter + Geist Mono)

**File Structure:**
```

- index.html
- index.css
- src/assets/
  - fonts/ # all downloaded fonts
  - png/ # all png format images
  - svg/ # all vector images
- src/styles/
  - base.css # fonts, globals,reset, buttons
  - layout.css # header, footer, containers
  - section.css # hero, features, reviews etc

```

I split the CSS into three files to keep things organized:
- `base.css` — global styles and utilities
- `layout.css` — header, footer, and shared layouts
- `sections.css` — page-specific sections

and import into index.css root file for better management and readability

---

## How to Run

No setup needed. Just open `index.html` in your browser.

**For a better experience:**
- Use **Live Server** in VS Code

---

## What I Learned

- How to build responsive layouts with Flexbox and Grid
- Why organizing CSS matters (especially without a framework)
- How to structure HTML that's clean and easy to read
- The value of keeping things simple

---

## Here is Preview


## What's Next

Some ideas I might add later:
- Mobile responsiveness
- Dark mode toggle
- Smooth animations
- Better accessibility

---

## Credits

Design inspired by [Mintlify](https://mintlify.com). Built purely for practice.

```
