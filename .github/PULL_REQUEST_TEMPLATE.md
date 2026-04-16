<!--
PR title: Short, descriptive title

Important: Every PR MUST include at least 5 books in the library.
Acceptable formats:
- Create/modify files under the library/ directory (markdown/text/JSON files), OR
- Add/modify books.json (top-level array or {"books":[ ... ]}) with at least 5 entries.

Please fill out the checklist below before opening the PR.
-->

## Summary
<!-- Brief description of the change and why it is needed -->

## Library changes (REQUIRED)
- Which files did you add or change under `library/` or `books.json`?
  - Example: `library/book-1.md`, `library/book-2.md`, `books.json`

## Checklist (all required)
- [ ] I confirm this PR includes at least 5 books in the library (files in `library/` or entries in `books.json`).
- [ ] Each book includes a title and author.
- [ ] Each book has a short description (1-3 sentences) or metadata where applicable.
- [ ] I updated any relevant docs or README if the structure changed.
- [ ] The repository builds/tests (if applicable) pass locally.

## Example book JSON format
You can provide books as a top-level array or as the value of a `books` key.

Top-level array:
```json
[
  { "title": "Book One", "author": "Author A", "notes": "Short note" },
  { "title": "Book Two", "author": "Author B" },
  { "title": "Book Three", "author": "Author C" },
  { "title": "Book Four", "author": "Author D" },
  { "title": "Book Five", "author": "Author E" }
]
```

books.json with `books` key:
```json
{
  "books": [
    { "title": "Book One", "author": "Author A" },
    { "title": "Book Two", "author": "Author B" },
    { "title": "Book Three", "author": "Author C" },
    { "title": "Book Four", "author": "Author D" },
    { "title": "Book Five", "author": "Author E" }
  ]
}
```

If you add individual files under `library/`, prefer one file per book (e.g., `library/book-title.md`) with at least:
- Title (H1 or frontmatter)
- Author
- Short description

Thank you for contributing!