# EDA6931 Summer 2026 — Slide Decks

Public GitHub Pages site for slide decks used in EDA6931 (Quantitative Methods in Educational Administration), Summer 2026.

**Live site:** https://ehuffaker.github.io/eda6931-summer2026-slides/

## Structure

```
module_N/
  saturday_session/
    module_N_saturday_slides.html
    module_N_saturday_slides_files/
    images/
    custom.css
```

## Publishing a new / updated deck

1. Render the source Quarto deck (e.g. from `Summer2026/Module 1/saturday_session/quarto/`):
   ```
   quarto render module_1_saturday_slides.qmd
   ```
2. Copy the rendered output into the matching folder here.
3. Commit and push:
   ```
   git add . && git commit -m "Update Module N Saturday slides" && git push
   ```
4. GitHub Pages redeploys in ~30 seconds.
