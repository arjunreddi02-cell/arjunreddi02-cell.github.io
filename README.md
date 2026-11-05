# Harish Reddy — Hybrid AI Director

Portfolio website: **https://arjunreddi02-cell.github.io**

*Machines make footage. I make films.*

## How to update the site

Everything on the page comes from one block at the top of `index.html`, marked **EDIT YOUR SITE HERE**.

1. Open `index.html` in this repository and click the pencil icon (**Edit this file**).
2. Change the text between the quotes.
3. Click **Commit changes**. The live site updates in about a minute.

### Add a new film
1. In `index.html`, copy one `{ ... }` block inside `work: [ ... ]`, paste it at the top of the list and change:
   - `category`: `"Films"`, `"AI Films"`, `"Cinematic Demos"` or `"Commercial Ads"` (to add a new tab, also add its name to `categories`)
   - `role`: your role, e.g. `"Director"`, `"Assistant DOP"`
   - `video`: a YouTube, Vimeo or Google Drive link. It plays on your page in a pop-up player. Drive files must be shared as "Anyone with the link".
   - `image`: leave `""` and the thumbnail comes from the video automatically. For your own, upload it to `media/` and write e.g. `"media/my-film.jpg"`.
   - `status`: `"Released"`, `"In production"`, `"Post-production"` or `"Coming soon"`
2. Commit. Keep the commas between blocks.

### Change your photo
Upload the new photo (Add file → Upload files), then change `photo: "harish_portrait.jpg"` in `index.html` to the new file name.

## Files
- `index.html` — the whole website
- `harish_portrait.jpg` — your hero photo
- `media/` — thumbnails and short clips (create it the first time you upload one)
