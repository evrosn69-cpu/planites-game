# Πλανήτες και Τέρατα: installable app

This folder is the whole app. Upload it to a free website once, then install it on any phone, tablet or computer.

## 1. Put it online with GitHub Pages (free, about 10 minutes)

1. Make a free account at github.com.
2. Click **+** (top right), then **New repository**.
   - Name it something like `planites` (this becomes part of the web address).
   - Choose **Public**, then click **Create repository**.
3. On the new page, click **uploading an existing file**.
4. Drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js` and the `icons` folder.
   Then click **Commit changes**.
5. Go to **Settings**, then **Pages** (left menu).
   - Under "Branch", pick **main** and **/ (root)**, then click **Save**.
6. Wait a minute or two and refresh. The address appears at the top, like
   `https://YOUR-NAME.github.io/planites/`

Open that address once while online so the app saves itself for offline play.

## 2. Install it

- **iPhone / iPad:** open the address in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open it in **Chrome**, tap the menu (three dots), then **Install app** (or "Add to Home screen").
- **Windows:** open it in **Chrome** or **Edge** and click the install icon at the right of the address bar.
- **Mac:** in **Chrome**, click the install icon in the address bar; in **Safari**, choose **File**, then **Add to Dock**.

The game then opens from its own icon, full screen, and works without internet.

## 3. Updating the game later

1. Upload the new `index.html` to the same GitHub repository (it replaces the old one).
2. Open `sw.js`, change `planites-v1` to `planites-v2` (then v3, and so on), and upload it too.
3. Open the app while online; it picks up the new version, and from the next launch on everyone has it.

## Good to know

- Progress (unlocked planets) is saved on each device separately.
- On phones the game is easiest to play with the phone turned sideways.
- The pixel font is saved the first time the app opens online. If you ever install it while offline, the text shows in a plain font until the next time it's online.
