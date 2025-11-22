# Journaling2025

How to generate a epub ebook from markdown files?

```
$ cd Nov & pandoc \
  *.md \
  --metadata-file=meta.yaml \
  --epub-title-page=false \
  --toc \
  --toc-depth=1 \
  -o Nov\ 2025.epub
```