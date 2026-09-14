MIST
A local HTML game launcher
===========================

WHAT IS THIS?
-------------
Mist is a single self-contained HTML file that turns any folder of
HTML5 games into a slick, Steam-style library. There's no server,
no install, and no internet connection required — everything runs
and saves right inside your browser, on your own device.

Open mist.html, create an account, and start dropping in .html
game files. That's it.


KEY FEATURES
------------
- Steam-like library UI: grid view, search, sorting, and per-game
  detail pages with cover art, tags, description, and play stats.
- Add games two ways: upload an .html file, or paste raw HTML
  source directly into the app.
- Track playtime, launch count, and last-played date for every
  game automatically.
- Edit game properties any time (title, author, description, tags,
  cover art) or replace a game's underlying file without losing
  its history.
- Built-in Store and Community tabs for a browsable "featured
  game" and profile view of your own library.
- One-click backup to a JSON file (your account + full game
  library + all HTML) and restore from that file on any device.
- Everything is 100% local. Nothing is ever uploaded anywhere.


ACCOUNTS & SIGNING IN
----------------------
- The first time you open Mist, you'll create a local account
  (a username, password, and optional avatar).
- Mist remembers your account name so it's pre-filled on the
  sign-in screen — but it will ALWAYS ask for your password.
  There's no "remember me" / stay-logged-in option, by design,
  so your library stays private on shared or public devices.
- Signing out is available from the account menu (top right)
  at any time.


PLAYING A GAME
---------------
- Click any game in your library, then hit Play.
- Games always launch in their own separate popup window, sized
  and centered automatically. This keeps the game fully isolated
  from the Mist library window.
- That popup window's address bar always shows "about:blank" —
  the game itself is loaded inside it, but the real file address
  is never shown in the URL bar.
- Just close the popup window when you're done. Mist automatically
  logs how long you played and updates your stats.
- If your browser blocks the popup, allow popups for this page
  and try launching again.


MANAGING YOUR LIBRARY
-----------------------
- Search your library by name using the search bar in the sidebar.
- Sort by Recently Played, Date Added, Name, or Play Time.
- Right-click (or use the gear icon on) any game for quick actions:
  Play, Properties, Replace game file, or Remove from library.
- Properties lets you rename a game, update its author/description/
  tags, or change its cover art without touching the game file.


ACCOUNT SETTINGS
------------------
Open the account menu, top right, to reach:
- Profile — change your display name and avatar.
- Account — change your local password.
- Data — back up your library to a file, restore from a backup,
  view how much storage you're using, or wipe everything and
  start fresh.


BACKUP & RESTORE
-------------------
- "Back up library…" saves a single JSON file containing your
  account, your full game list, and the raw HTML of every game.
- "Restore from backup…" reads that file back in on this device
  or any other copy of Mist, fully replacing your current library.
- Keep your backup file somewhere safe — it's the only copy of
  your library outside this browser.


WHERE YOUR DATA LIVES
------------------------
Mist saves everything locally using, in order of preference:
  1. IndexedDB (best — handles large libraries smoothly)
  2. localStorage (fallback if IndexedDB isn't available)
  3. In-memory only (last resort — nothing survives a refresh;
     Mist will warn you if this happens)
No data is ever sent to a server. Uninstalling/clearing your
browser data for this page will erase your library unless you've
made a backup.


KEYBOARD SHORTCUTS
---------------------
- Esc — closes any open dialog/modal.


TIPS
------
- Give games good titles and cover art — it makes the library
  grid look great.
- Use tags (comma-separated) to keep a big library organized and
  searchable.
- Back up regularly, especially before clearing browser data or
  switching devices.


-------------------------------------------
Mist — your games, your device, your rules.
-------------------------------------------
