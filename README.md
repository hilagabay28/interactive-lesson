# Interactive Lesson (Vue.js)

A mobile-first interactive learning module ("לומדה") built with **Vue 2**. The learner moves through short content screens and practices with several kinds of interactive exercises, each checked instantly.

**▶ Live demo: https://hilagabay28.github.io/interactive-lesson/**

> **Note:** all the learning text in this repository is placeholder text (Hebrew *Lorem Ipsum*). The original content was removed for information-security reasons, and a notice about this is shown at the bottom of every screen. The structure, design and exercise logic are the original work.

## Exercise types

- **Drag to sort** — put steps in the right order (`vuedraggable`).
- **Drag and match** — drag each option onto the description it belongs to.
- **Draw lines** — connect items in two columns with lines.
- **Multiple choice** and **select several answers**.
- **Advantages / drawbacks table** — match methods to their pros and cons.

Each exercise has a "check me" button that shows whether the answer is right and lets the learner try again.

## Built with

- Vue 2, Vue CLI
- `vuedraggable` for drag and drop
- `animate.css` for transitions
- All content lives in one JSON file (`text.json`), so the same components can show a different lesson just by changing the data.
- Right-to-left (Hebrew) layout, custom fonts, designed for phone screens.

## Running it

```bash
npm install
npm run serve
```

Then open the address it prints. The lesson is designed for phones, so shrink the browser window or use the browser's mobile view.

To build a static version (for example for GitHub Pages):

```bash
npm run build
```
