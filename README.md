# Sydney Spector College Counseling

A single-file static website. Everything — HTML, CSS, JavaScript, and the one
photo (embedded as a base64 data URI) — lives in `index.html`. There's no
build step and no other assets to manage.

## Editing the copy

1. Open `index.html` in any text editor.
2. Find the section you want to change (search for the heading text, e.g.
   `<section id="contact">` for the Contact section).
3. Edit the text directly between the HTML tags. Don't touch anything
   inside `<script>` or `<style>` tags unless you mean to change behavior
   or appearance.
4. Save the file, then preview it by opening `index.html` directly in a
   browser (double-click it) before publishing.

## Publishing changes

This site is hosted on GitHub Pages. To publish an edit:

```
git add index.html
git commit -m "Update copy"
git push
```

The live site updates automatically within a minute or two of pushing to
`main`.

## Contact email placeholder

The Contact section and the mailto script at the bottom of `index.html`
currently use a placeholder email address. Search for it and replace both
occurrences with the real contact email before sharing the site widely.
