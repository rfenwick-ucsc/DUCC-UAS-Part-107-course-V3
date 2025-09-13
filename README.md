# DUCC Course Markdown Export

This folder contains Markdown converted from the Canvas/IMS export, suitable for Git/GitHub.

- Converted pages are in `course/` (if a manifest-defined structure was detected) or mirrored by original folders.
- All assets are under `assets/` with relative links updated in the Markdown.
- A navigable outline is in `SUMMARY.md`.

## Suggested Repo Layout
```
/
├─ course/         # Markdown pages by sections (if IMS manifest provided)
├─ assets/         # Images, PDFs, docs referenced by pages
├─ SUMMARY.md      # Table of contents with page links
└─ README.md
```

> Conversion is best-effort. If you notice a page with odd formatting (especially complex tables), open an issue and attach the page name for a targeted fix.
