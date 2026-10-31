# Money Tracker (offline app)

Works with no internet and no server. All data stays on the phone.

## Test it on your computer
    cd money_tracker_offline
    python3 -m http.server 8000
Open http://localhost:8000

## Put it online once (free, needed only for the first install)
1. Make a NEW GitHub repo, for example `money-tracker-app`.
2. Upload every file in this folder (not the old Flask files).
3. Repo Settings -> Pages -> Deploy from branch -> `main` and `/ (root)` -> Save.
4. Wait a minute. Your link looks like https://YOUR-NAME.github.io/money-tracker-app/

## Install on your phone
- iPhone (Safari): open the link -> Share -> Add to Home Screen.
- Android (Chrome): open the link -> menu -> Install app.
Then open the app once from its icon while online. After that, airplane mode works.

## Updating the app later
Change the number in `sw.js` (`money-tracker-v1` -> `money-tracker-v2`) whenever you edit any file,
then upload the files again. Phones pick up the update the next time they open the app online.

## Your data
- Saved on each phone only. Ten people can use it, and each has their own data automatically.
- Deleting the app or clearing browser data erases it. Use "Backup and restore" in the app to keep a copy.
