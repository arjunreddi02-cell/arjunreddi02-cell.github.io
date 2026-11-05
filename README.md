# Harish Reddy — Hybrid AI Director

Portfolio website: **https://arjunreddi02-cell.github.io**

*Machines make footage. I make films.*

## How to update the site

Everything on the page comes from one block at the top of `index.html`, marked **EDIT YOUR SITE HERE**.

1. Open `index.html` in this repository and click the pencil icon (**Edit this file**).
2. Change the text between the quotes.
3. Click **Commit changes**. The live site updates in about a minute.

### Add a new film
1. Upload a thumbnail (16:9 JPG, about 1600×900) to the `media` folder: **Add file → Upload files**.
2. In `index.html`, copy one `{ ... }` block inside `work: [ ... ]`, paste it at the top of the list and change:
   - `category`: `"Commercial Ads"`, `"Cinematic Demos"`, `"Wildlife & Natural History"` or `"Sound"` (a new name creates a new tab)
   - `image`: e.g. `"media/my-film.jpg"`
   - `video`: a YouTube or Vimeo link. It plays on your page in a pop-up player. Short clips (under 25 MB) can be uploaded to `media/` as `.mp4`.
   - `status`: `"Released"`, `"In production"` or `"Coming soon"`
3. Commit. Keep the commas between blocks.

### Change your photo
Upload the new photo (Add file → Upload files), then change `photo: "harish_portrait.jpg"` in `index.html` to the new file name.

## Files
- `index.html` — the whole website
- `harish_portrait.jpg` — your hero photo
- `media/` — thumbnails and short clips (create it the first time you upload one)
