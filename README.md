# DumDum

Turns an iPhone into a dumb phone without deleting anything.

- A black and white home screen web app with eight things: Phone (with saved people and a call log), Text, Email, Calendar, Directions, Clock, shuffle-only Music, Search.
- A built-in setup checklist that creates a "Dumb" Focus mode: one switch hides other apps, closes them if opened, quiets notifications and turns the screen greyscale. It does not use Screen Time or Downtime.

Every app stays installed and comes back the moment Dumb mode is switched off.

## Put it on your phone

1. In this repository on GitHub: **Settings → Pages → Deploy from a branch**, choose the branch and `/ (root)`, save.
2. After a minute, open `https://<your-username>.github.io/dumdum/` in Safari on the iPhone.
3. Follow the Setup tab. Step one adds DumDum to the Home Screen.

## Why it is not a native app

iOS does not let an app replace the home screen or close other apps. DumDum gets the same effect with a Focus mode and a few Shortcuts automations that you set up once, so no Mac, Xcode or developer account is needed.

## Files

- `index.html`: the whole app (home screen and setup checklist)
- `manifest.webmanifest`, `icon-*.png`: Home Screen icon and name
- `sw.js`: keeps it working offline
