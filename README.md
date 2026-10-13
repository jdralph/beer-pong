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
- iPhone Safari can clear a website's saved data after about a week of not opening it. Apps added to the Home Screen are exempt, but the Home Screen version keeps its own separate data from the Safari tab. Pick one and stick with it.

**Keep a backup in iCloud Drive (iPhone):**
1. Open the **Players** tab and scroll to **Backup**.
2. Tap **Save to Files**. The iPhone share sheet opens.
3. Tap **Save to Files** in the share sheet, choose a folder in **iCloud Drive**, and tap **Save**.
4. After each **Save and start again**, the app asks **Back Up Now?** Tap **Save to Files** to do it in one step.

To restore, tap **Restore from backup** and pick the file from Files. On a device that can't open the share sheet, Save to Files downloads the file instead.

---

## Quick guide
- **Players tab:** add everyone with a name and nationality. Tap a player to see their stats: games, record, win rate, average cups per game, average cup difference per game, best win streak, cups for and against, tournaments and titles.
- **Past Tournaments** (Players tab): every saved tournament is listed. Tap one to see its champion, ladder or standings and every game result. You can remove one there, and its games leave the player stats.
- **Start Again** (Setup tab, after a tournament): **Save and start again** adds it to Past Tournaments and the stats. **Don't save, start again** throws the results away.
- **Setup tab, Live draw:** tick who is playing (4 or more), tap **Start live draw**. Choose Auto or Tap to reveal first.
- **Setup tab, Game rules:**
  - **Match length:** 1 game, Best of 3 or Best of 5. A series is scored like sets in tennis, and the sheet reopens for the next game until someone has enough wins.
  - **Cups per game** (default 6), an optional **game timer**, and for round robin: draws and a points table.
- **Round robin finals:** pick what happens after the ladder. "1v4" means 1st plays 4th.
  - **No Finals:** the ladder decides it.
  - **Grand Final** (1 game): 1v2 decides the title.
  - **Top 3 Finals** (2 games): 2v3. The winner plays 1st in the Grand Final.
  - **Top 4 Finals** (3 games): 1v4 and 2v3. The winners play the Grand Final, the losers are out.
  - **Page Playoff** (4 games): 1v2 and 3v4. The 1v2 winner goes straight to the Grand Final. 3v4 is elimination. The 1v2 loser plays the 3v4 winner for the other spot.
  - **Top 5 Finals** (5 games): 1st gets a bye. 2v3 and 4v5, where 4v5 is elimination. The 2v3 winner plays the 4v5 winner, and the 2v3 loser plays 1st. The winners play the Grand Final.
- **Two teams:** pick Single knockout for a head to head, with Best of 3 or 5 if you like.
- **Score tab:** tap a game. The timer (or a game clock that counts up, if the timer is off) sits at the top. Tap **Start game** and the card shows **In game** with its time. Other games with those teams show **Unavailable** until it ends.
- **Result?:** tap the winning team and use + and − for the cups the losers sunk. Go above 6 for overtime.
- **Timer:** stops as soon as you pick a winner (tap Resume if that was a mistake). It turns red in the last minute, with a 1 minute warning sound and a siren at the end. When time is up, enter the cups and tap **Call it**. A **Draw** button appears once time has run out.
- **Keep the app open and the screen on during a timed game.** Phones can pause sounds when the screen locks.

---

## If something goes wrong
- **Page shows 404:** wait another minute or two, then refresh. The first publish can be slow.
- **Settings has no Pages option:** the repository is probably Private. Make it Public under Settings, Danger Zone.
- **Changes not showing after an update:** refresh the page twice, or close and reopen the app.
