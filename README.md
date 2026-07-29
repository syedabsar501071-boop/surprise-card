# A Special Surprise ❤️

A small, single-page romantic surprise site: a welcome screen, a letter, tap-to-reveal
reason cards, a photo gallery, and a final note — with background music and a floating
hearts animation.

## How to use this repo

### 1. Add your own photos
This repo ships with 5 placeholder images in the `images/` folder so the page works
right away. To use your real photos:

1. Pick 5 photos you want to show.
2. Rename them exactly: `photo1.jpg`, `photo2.jpg`, `photo3.jpg`, `photo4.jpg`, `photo5.jpg`
   (If your photos are `.png` instead of `.jpg`, just also update the file extension in
   `index.html` in the `<img src="images/photo1.jpg">` lines to match.)
3. Upload them into the `images/` folder in this repo, overwriting the placeholders.

That's the only step needed — the page automatically shows whatever is in `images/`.

### 2. Edit the message
Open `index.html` and look for the comments starting with `✏️ TO EDIT`. There are two spots:
- The main letter text (Scene 2)
- The four "reason" notes (Scene 3), inside the `revealReason(this, '...')` calls

Just change the text between the quotes and save.

### 3. Publish it as a live link (GitHub Pages)
1. Create a new repository on GitHub and upload these files (`index.html`, the `images/`
   folder, and this `README.md`) keeping the same folder structure.
2. Go to your repo's **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, choose your
   main branch and the `/ (root)` folder, then save.
4. GitHub will give you a live URL (usually `https://yourusername.github.io/reponame/`)
   within a minute or two — that's the link you can send.

### Notes
- If you'd rather keep this private, you can make the repo private — note that GitHub
  Pages for private repos requires a paid GitHub plan; otherwise just share the repo
  or the file directly instead of using Pages.
- There's no edit button or upload feature on the live page itself — only you, editing
  the files in the repo, can change the photos or text.
