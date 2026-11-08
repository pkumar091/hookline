# Hookline: YouTube auto-DJ

One file: `index.html`. YouTube's player only works on pages served from a web address, not on a file you double-click, so use one of these:

## Quickest: run it on your laptop
1. Put `index.html` in a folder.
2. Open a terminal in that folder and run: `python3 -m http.server 8000`
3. Open http://localhost:8000 in Chrome.

## Free link you can open anywhere (GitHub Pages)
1. On github.com, create a new public repo (e.g. `hookline`).
2. Click **Add file → Upload files**, upload `index.html`, then commit.
3. Go to **Settings → Pages**. Under "Branch" pick `main` and `/ (root)`, then click Save.
4. After about a minute your DJ is live at `https://<your-username>.github.io/hookline/`

## Using it
- **Auto**: hit Start. It picks songs from the languages you've selected, starts each one at its hook and mixes into the next.
- **DJ mode**: nothing mixes until you say so. Drag the crossfader, or press **Mix now** (M). The next song is always loaded on the other deck.
- **📍 Mark hook here** (H): if a song starts in the wrong spot, press this when the chorus hits. It's saved in your browser for next time.
- **Add any song**: paste a YouTube link in the Library box.
- Shortcuts: Space = pause, M = mix now, S = skip, H = mark hook.

Notes: some videos can show YouTube ads, which can interrupt a transition. Being signed in to YouTube Premium avoids them. Hook marks and pasted songs are saved per browser.
