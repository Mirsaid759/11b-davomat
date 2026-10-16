11-B Davomat — public demo

This repository contains the public demo version of the attendance website.

Important:
- The current public version uses browser localStorage for attendance data.
- Student accounts are created in the browser by adding a username to the student list and reloading the page in the same browser.
- This is suitable for a quick public demo, but it is not secure for real production use.

For a production version, move authentication and attendance storage to Firebase Authentication + Firestore.

Quick GitHub Pages publish steps:
1. Push this repo to GitHub.
2. Go to Settings → Pages.
3. Set source to the `main` branch and `/ (root)`.
4. Save.

Then your site will be live at:
https://mirsaid759.github.io/11b-davomat/
