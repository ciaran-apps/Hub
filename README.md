# App Hub

All of Ciaran's apps in one place, with change requests. Live at **https://apps.ciarandevine.uk** (open in Chrome and choose **Install app**).

## How requests work

- Each request is a GitHub issue in this repo, labelled with the app's id (for example `work-tt`). The app's "Continue in GitHub" button opens a pre-filled issue; tap **Submit new issue**.
- Say **"do my app requests"** to Claude. It reads the open issues here, makes each change in the app's own repo, comments with what it did and closes the issue. Labels `in-progress` and `needs-info` show where a request is up to.
- `apps.json` is the list of apps (id, title, repo, owner, live address). Add new apps here.

Files: `index.html` (the whole app), `apps.json`, `sw.js` + `manifest.json` + icons (installable, opens offline), `CNAME` (custom address).
