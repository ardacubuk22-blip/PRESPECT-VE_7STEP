# perspective.sketch – free cheat sheet site

A small static website (plain HTML + CSS, no build step) where visitors from Instagram can download the
**7 Types of Perspective** cheat sheet as a PDF.

```
index.html            the landing page
assets/style.css      styles
assets/img/           cover and page previews (rendered from the PDF)
downloads/            the PDF files people can download
```

## Preview locally

Open `index.html` in a browser, or run `npx serve .` in this folder.

## Publish for free (GitHub Pages)

1. Repository **Settings → Pages**.
2. **Source:** Deploy from a branch → branch `main`, folder `/ (root)` → Save.
3. After a minute the site is live at `https://<user>.github.io/<repo>/`. Put that link in the Instagram bio.

## Adding more downloads or books later

- Put the new PDF in `downloads/` and add a card next to the "More books coming soon" section in `index.html`.
- For paid books, the usual route is a hosted checkout (e.g. a payment link) per book; the page structure
  is ready for a `books` section.
