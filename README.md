# Book Template

A reusable control-layer and research-layer template for book projects. This template treats the control layer as the stable spine of any book, with a portable, modular research layer that can travel across projects.

## Structure

```
000-Index.md
00-book-control/
  book-charter.md
  book-argument-map.md
  chapter-status.md
  book-decision-log.md
  book-memory.md
01-outline/
  book-outline.md
02-manuscript/
03-research/
  00-research-map.md
  themes/
  syntheses/
  reusable-notes/
04-patterns-and-diagrams/
05-publication-assets/
99-archive/
```

## How to use this template

1. Copy this repository (or use it as a GitHub template) for each new book project.
2. Fill in `00-book-control/book-charter.md` first — everything else should trace back to it.
3. Build `00-book-control/book-argument-map.md` to connect the charter's thesis to specific, testable claims.
4. Use `00-book-control/chapter-status.md` as the operating dashboard while writing.
5. Log any decision that changes thesis, scope, or structure in `00-book-control/book-decision-log.md`.
6. Keep `00-book-control/book-memory.md` running between sessions for unresolved threads and fragments.
7. Populate `03-research/` incrementally — themes for topic research, syntheses for claim-specific evidence, and reusable-notes for concepts likely to reappear in future books.

See `000-Index.md` for the live map of any given project once control documents are filled in.
