# Plumb & Alder Home Builders (sample contractor site)

A static website: one `index.html` and an `assets/` folder. No build step.

## Put it online with GitHub Pages
1. Create a repository and upload `index.html` and the `assets` folder to its root.
2. In the repository, open Settings, then Pages, and publish from the main branch (root folder).
3. Your link will look like `https://USERNAME.github.io/REPO/`.
4. Open `index.html`, find the `DEPLOY STEP` comment near the top, and replace the two `og:` addresses with your live link so link previews show the kitchen photo.

## Preview on your computer
Double-clicking `index.html` shows the still version of the hero. To see the scroll animation, run a tiny local server in this folder, for example `python3 -m http.server`, then open `http://localhost:8000`.

## Customize it for a real client
- Name and copy: search `index.html` for "Plumb" and "Alder" and replace with the client's name. Edit headlines, services and FAQ answers in place.
- Colors: the `:root` block at the top of the style section holds every color. `--accent` is the blue used for buttons and the chalk line.
- Photos: replace the files in `assets/` with the client's real before and after photos (keep each pair the same size and framing). Update the two lines of alt text for each project.
- Hero video: replace `assets/hero-scrub.mp4`, `hero-poster.jpg` and `hero-ending.jpg`, and update `VIDEO_BYTES` in the script to the new file size.
- Quote form: it only shows a thank-you message. Connect it to the client's email or a form service before going live.
- Remove the sample disclosure in the footer, add the client's real phone, city and reviews.

All photos and the video in this sample were AI generated.
