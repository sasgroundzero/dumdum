# DumDum

Turns an iPhone into a dumb phone without deleting anything.

- A black and white home screen web app with five things: Phone, Text, Email, Directions, Search.
- A built-in setup checklist that uses iOS Screen Time to block every other app all day, and Color Filters to make the screen greyscale.

Every app stays installed. They are hidden and blocked, and come back when you turn Downtime off.

## Put it on your phone

1. In this repository on GitHub: **Settings → Pages → Deploy from a branch**, choose the branch and `/ (root)`, save.
2. After a minute, open `https://<your-username>.github.io/dumdum/` in Safari on the iPhone.
3. Follow the Setup tab. Step one adds DumDum to the Home Screen.

## Why it is not a native app

iOS does not let an app replace the home screen, and the only way an app can block other apps is Apple's Screen Time system, which is already built into Settings. DumDum walks you through that directly, so no Mac, Xcode or developer account is needed.

## Files

- `index.html`: the whole app (home screen and setup checklist)
- `manifest.webmanifest`, `icon-*.png`: Home Screen icon and name
- `sw.js`: keeps it working offline
