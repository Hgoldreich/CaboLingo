# CaboLingo 4.6 Production Stable

Upload all files to GitHub root.

Purpose:
- Stable production version for Hilton and Liz to use daily.
- Keeps lessons, quiz, progress, sync, home-screen icon, and stable games.
- Adds a visible version badge on phone.
- Manifest start_url is now "/" so the Home Screen icon opens the main app instead of an old ?v= link.

After Amplify deploys:
1. Test https://cabolingo.com/?v=46
2. If it works, delete the old Home Screen icon.
3. Open https://cabolingo.com
4. Share → Add to Home Screen.

Do not add experimental games to production. Build them on dev first.
