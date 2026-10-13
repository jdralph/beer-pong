# Beer Pong Tournament

A tournament app for beer pong nights. Player profiles with flags, a live team draw, cup scoring, optional game timer, and career stats for every player.

Runs in any phone or computer browser. No install, no sign-up, no server.

---

## How to put it online (GitHub Pages)

You only do this once. It takes about 5 minutes and costs nothing.

### 1. Make a GitHub account
Go to **github.com** and sign up. Skip this if you already have one.

### 2. Make a new repository (a folder for your app)
1. Click the **+** at the top right, then **New repository**.
2. Repository name: `beer-pong` (or anything you like, no spaces).
3. Choose **Public**. GitHub Pages is free for public repositories only.
4. Tick **Add a README file**.
5. Click **Create repository**.

### 3. Upload the app
1. On your new repository page, click **Add file**, then **Upload files**.
2. Drag **all three files** onto the page: `index.html`, `apple-touch-icon.png` and `icon.svg`. The main file must be called exactly `index.html`. The other two are the six-cup icon for your home screen.
3. Scroll down and click **Commit changes**.

### 4. Turn on GitHub Pages
1. Click **Settings** (top row of the repository).
2. Click **Pages** in the left menu.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Under **Branch**, choose **main** and **/ (root)**, then click **Save**.
5. Wait 1 to 2 minutes, then refresh the page. A green box appears at the top with your link:

   `https://YOUR-USERNAME.github.io/beer-pong/`

That link is your app. Send it to anyone.

### 5. Put it on your phone's home screen
- **iPhone (Safari):** open the link, tap the **Share** button, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the **three dots**, then **Add to Home screen**.

---

## Updating the app later
Repeat step 3. Upload the new `index.html` (the icon files only need uploading once). GitHub asks if you want to replace the old one, so say yes. Your players and stats are not affected, because they live in your browser, not in the file.

---

## Important: where your data lives
Players, stats and tournaments are saved **in the browser on the device you use**. That means:

- Your phone and a friend's phone each have their own separate players list.
- Clearing your browser data or using a private tab erases it.

Protect your stats: open the **Players** tab, scroll to **Backup**, and tap **Download backup** every so often. **Restore from backup** puts everything back, including on a new phone.

---

## Quick guide
- **Players tab:** add everyone with a name and nationality. Tap a player to see their stats.
- **Setup tab, Live draw:** tick who is playing, tap **Start live draw**. Choose Auto or Tap to reveal first.
- **Setup tab, Game rules:** cups per game (default 6), optional game timer, draws and a points table (round robin only).
- **Score tab:** tap a game, tap the winning team (they start on 6 cups), use + and − for the cups the losers sunk. Go above 6 for overtime.
- **Timer:** if on, tap Start in the score sheet. When time is up, enter the cups and tap **Call it**.

---

## If something goes wrong
- **Page shows 404:** wait another minute or two, then refresh. The first publish can be slow.
- **Settings has no Pages option:** the repository is probably Private. Make it Public under Settings, Danger Zone.
- **Changes not showing after an update:** refresh the page twice, or close and reopen the app.
