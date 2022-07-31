Render with:

```bash
pandoc \
  --to=beamer \
  --include-in-header=./preamble.tex \
  --standalone \
  --slide-level 2 \
  --output=../rendered_slides/git.pdf git.md
```