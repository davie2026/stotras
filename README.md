# Ram Raksha Stotra — Interactive Site

Interactive web experience for the श्रीरामरक्षास्तोत्रम्: all 38 shlokas as 3D
papyrus cards in pure Devanagari Sanskrit, with English and Hindi meanings on
every card.

Features:

- 3D card-stack navigation — swipe, Previous/Next buttons, keyboard arrows
- Draggable progress scrubber to jump to any shloka
- Fast rendering (only the active card is in the DOM), synced progress counter
- Mobile-first, single-column layout

## Run locally

Open `index.html` in any browser. No build step, no server needed.

## Host on GitHub Pages

1. Create a new GitHub repo and push these files:

   ```sh
   git init
   git add .
   git commit -m "Ram Raksha Stotra site"
   git branch -M main
   git remote add origin git@github.com:<you>/<repo>.git
   git push -u origin main
   ```

2. In the repo: Settings → Pages → Deploy from a branch → `main`, `/ (root)`.
3. Your site goes live at `https://<you>.github.io/<repo>/`.

Built with Muse.
