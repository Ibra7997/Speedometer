## 2024-10-04 - Accessible Layout Refresh Button
**Learning:** Found icon-only `<button id="layout">` elements in the tiptap and codemirror editors that lacked `aria-label` and `title` attributes.
**Action:** Always ensure icon-only buttons have descriptive `aria-label` (for screen readers) and `title` (for mouse hover tooltips).
