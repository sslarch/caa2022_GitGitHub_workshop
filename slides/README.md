Render the slides with the following command:

```bash
pandoc \
  --to=beamer \
  --include-in-header=./preamble.tex \
  --standalone \
  --slide-level 2 \
  --output=../rendered_slides/git.pdf git.md
```

This will only work properly for `git.md` with a recent version of pandoc