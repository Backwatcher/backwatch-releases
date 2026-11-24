# Backwatch version history

What changed in each version of Backwatch, newest first.

**To update:** download the newest Backwatch-Mac.dmg (the download button always gives you the newest version), quit Backwatch, then drag the new Backwatch into your Applications folder and choose **Replace**. Your library, folders, rules, notes, favorites, backups and serial number are kept: they're stored separately from the app.

Like every update, your Mac asks once before opening the new version: go to **System Settings → Privacy & Security** and click **Open Anyway**. The first time a new version opens, it re-sorts your library once in the background, so new sorting improvements reach your existing videos.

---

## Backwatch 0.9.250 (November 2026)

**Added**
- **Liked videos.** Every video you pressed Like on gets a thumbs-up and its own place in the Library list.
- **Search history.** See what you searched YouTube for and which searches you made most. Click any search to look for it in your library; if no video has every word, Backwatch shows the closest ones. You can remove your search history from Backwatch at any time, or turn it off in Settings.
- **Playlists**, with Watch later among them. Videos that are also in your watch history show in full; the rest are listed as links, because Google's file gives no titles for them.
- **Quick sort.** Clear Needs review fast: one channel at a time, filed with one key.
- **Move many videos at once.** Tick videos (or tick them all, for example after a search), then click Move, or drag any ticked video onto a folder: they all go together. Videos already in that folder stay put, so nothing is moved twice.
- **Choose folder** on every video in Needs review, to file it with a click instead of dragging.
- **Drag a whole channel** onto any folder to file all its videos.
- **Little lights** beside folders: green for videos new today, yellow for Needs review, red for No longer on YouTube.
- **Scams and Alerts**, a new folder sorted automatically: scams, fraud, rip-offs, consumer alerts and product recalls.
- **Unknown channels**, a folder for videos whose channel Google didn't name.
- **Russian in English.** An English button in the Русский folder shows Russian titles, channels and folders in English, translated on your Mac by Apple's own translator (macOS 15 or later; older Macs show Latin letters). Titles are never sent anywhere.
- **Update check.** About once a day Backwatch checks GitHub for a newer version and shows a Download card when there is one. It never downloads anything by itself, sends nothing about your library, and can be turned off in Settings.
- Every video in All videos says which folder it's in, including Needs review.
- **Sister channels.** A video from a channel like "Sony Pictures Television" goes where "Sony Pictures Entertainment" already is.
- **Check for duplicates** in Settings. Each YouTube video is kept once; importing again never makes copies.
- **Import history** in Settings: when you imported, which files, and how many videos were new. Copy it for support with one click.
- **Counts bar** at the bottom of the window: how many videos and channels you're looking at.
- **Back button** on every screen, and your own order for the Library list and topic folders (drag the rows).
- The **sort button** shows what's happening: blue and blinking while sorting, green "Sorted" when done, red "Re-sort" when enough has changed.

**Improved**
- Search treats singular and plural as the same word: "recipes" finds "recipe".
- Backwatch learns from your moves more carefully: everyday words like "these" or "people" no longer pull videos into the wrong folder.
- Moving videos no longer freezes the window, and Needs review opens and redraws much faster on big libraries.
- Lists settle so the bottom row is never cut off.
- You can drop a video on a folder that only holds other folders (like Русский); it goes there under its channel.
- The window opens where and as big as you last left it.
- Scroll bars on lists are orange and always showing.
- "No longer on YouTube" sits in the Library list, under Shorts.
- Needs review by channel is in A to Z order.
- The user guide covers everything new, with pictures in dark mode.

**Fixed**
- The window could freeze for many seconds while moving videos.
- A video with no channel name showed a stray dot at the start of its details.

**Removed**
- Nothing.

**After updating:** import your Google Takeout file once more to fill in Liked videos, Search history and Playlists. You won't get duplicates. For playlists, tick "playlists" as well as "subscriptions" when you ask Google for your file (the guide in the app shows where). Your Mac asks once more before opening the new version: System Settings → Privacy & Security → Open Anyway.

---

## Backwatch 0.9.206 (November 12, 2026)

**Improved**
- **Much faster with big libraries.** Opening Backwatch, opening and closing folders in the sidebar, and resizing the window are all far quicker. On a 57,000-video library the sidebar now redraws instantly instead of taking a couple of seconds each time.
- Subscriptions, On This Day and Favorites are counted once instead of over and over, which also speeds things up.

**Fixed**
- On This Day now judges every video against the same date, even if midnight passes while it's counting.
- A small behind-the-scenes fix so the folder list always refreshes after a sorting rule is saved.

**Removed**
- Nothing.

---

## Backwatch 0.9.188 (November 11, 2026)

**First public release.**
- Imports your YouTube watch history from Google Takeout (Backwatch opens Takeout with the right boxes ticked for you).
- Sorts every video automatically into folders by topic and by channel, in English, Spanish and Russian.
- Needs review groups the videos it isn't sure about by channel, so you can file a whole channel with one click.
- Search by title, channel, your own notes or a date ("yesterday", "Nov 9").
- Your Story (top channels, most rewatched, busiest hours, year by year), On This Day, Favorites and notes.
- Subscriptions list, folder colors, export to a spreadsheet or web page, backups with restore, Light and Dark mode.
- Private: everything stays on your Mac. No account, no cloud, nothing uploaded.
- Free version shows your newest 50 videos with all your real folders and counts; a $14.99 serial unlocks everything.
