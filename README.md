# José Fernando Rodríguez — Memorial Website

A memorial website for José Fernando Rodríguez (January 5, 1954 – May 3, 2026).

Live site: *(add your GitHub Pages URL here once published)*

---

## Updating the Photo Carousel

Photos in the carousel are hosted on [Imgur](https://imgur.com). To add or swap a photo:

1. Go to [imgur.com](https://imgur.com) and upload your photo
2. Once uploaded, right-click the image → **Copy image address**
   - The URL will look like `https://i.imgur.com/XXXXXXX.jpg`
3. Open `index.html` in any text editor (TextEdit on Mac, Notepad on Windows)
4. Find the carousel section — search for `carousel-slide`
5. Replace the `src="..."` on any slide with your new Imgur URL

To add a caption below a photo, add this inside the `<div class="carousel-slide">`:
```html
<div class="carousel-caption">Your caption text here</div>
```

---

## Funeral Service Information

| Service | Date | Time | Location |
|---|---|---|---|
| Visitation | Friday, May 8, 2026 | 6:00 PM – 8:00 PM | Curlew Hills Memory Gardens, 1750 Curlew Rd, Palm Harbor, FL 34683 |
| Funeral Talk | Saturday, May 9, 2026 | 3:30 PM – 4:30 PM | Kingdom Hall of Jehovah's Witnesses, 6404 N Church Ave, Tampa, FL 33614 |

---

## Updating the Obituary

The obituary appears in both Spanish and English. In `index.html`:

- Spanish text is inside `<div class="obit-text" id="obit-es">`
- English text is inside `<div class="obit-text" id="obit-en" hidden>`

Edit the text between the `<p>` tags as needed.

---

## iMessage / Social Media Preview

The site includes Open Graph meta tags so that sharing the URL in iMessage, WhatsApp, or Facebook generates a preview card with dad's portrait and the site title.

To update the preview image, find this line in `<head>` and replace the URL:
```html
<meta property="og:image" content="https://i.imgur.com/oWqfj9U.jpg" />
```

---

## Hosting

The site is a single `index.html` file — no build tools or dependencies required.

Hosted on **GitHub Pages** at:
`https://YOUR-USERNAME.github.io/jose-fernando-rodriguez`

To update the live site after making changes, go to the GitHub repository → drag the updated `index.html` into the file list → commit.

---

*Made with love by the Rodríguez family.*
