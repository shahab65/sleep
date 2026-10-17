# Sleep Dice

A calm, single-page app to help you fall asleep. Tap "I want to sleep", match the die to a card, and the next roll comes 5–15 seconds later.

It is one static file, `index.html`, with no build step and no dependencies.

## Run locally

Open `index.html` in a browser.

## Deploy

### GitHub Pages

1. Create a new repo on GitHub and push this folder:
   ```sh
   git init
   git add .
   git commit -m "Sleep Dice"
   git branch -M main
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
2. On GitHub, open the repo's **Settings → Pages**. Under **Source**, choose **Deploy from a branch**, then pick `main` and `/ (root)`, and click **Save**.
3. After a minute, the site is live at `https://<you>.github.io/<repo>/`.

### Vercel

1. Push to GitHub as above.
2. On vercel.com, click **Add New → Project**, import the repo, and keep all the defaults (Framework: Other, no build command).
3. Click **Deploy**.

You can also run `npx vercel` in this folder.
