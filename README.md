# The Story of Babyy Gurlll ❤️ — setup & deploy

## 1. Add her photos
Drop images into these folders, named plainly 1, 2, 3, 4 (jpg):

    assets/childhood/1.jpg ... 4.jpg
    assets/growing/1.jpg   ... 4.jpg
    assets/today/1.jpg, 2.jpg
    assets/us/1.jpg        ... 4.jpg
    assets/music/song.mp3   (optional)

Each folder has its own README.txt with the exact filenames expected.
If you have a different number of photos than the default, open
index.html, find the `PHOTOS` object near the top of the <script>
section, and change the `count` for that group.

## 2. Personalize the text
Open index.html and search for ✏️ — every mark shows you exactly what
to edit: the letter, the five "reasons I love you", the quiz answers,
and photo captions (search for things like [REASON_1] or
[CHILDHOOD_CAPTION_1]).

Also do a find-and-replace for:
- `[YOUR_NAME]` → your name

Her nickname "babyy gurlll" is already used throughout — search and
replace it if you'd rather use her real name or a different nickname.

## 3. Preview it
Just double-click index.html — it opens and runs in any browser,
no server or install needed.

## 4. Deploy to GitHub Pages (free, ~2 minutes)
1. Create a new GitHub repo (public), e.g. `for-babyy-gurlll`.
2. Upload this whole folder (index.html + assets/) to the repo —
   easiest via the GitHub web UI: "Add file → Upload files", drag
   everything in, commit.
3. Go to the repo's Settings → Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch",
   branch `main`, folder `/ (root)`. Save.
5. Wait ~1 minute, then your site is live at:
   https://<your-username>.github.io/<repo-name>/
6. Send her that link.

That's it — no backend, no database, no build step.
