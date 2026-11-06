# P6 MathConceptition 2026 — Questions 16–40

This public GitHub Pages repository contains only a landing page. **The question content, marking key, student names and results must stay outside this public repository.**

## Finish setup

1. Create a teacher-owned Google Sheet and note its ID from the Sheets URL.
2. In Google Apps Script create a project. Add **Code.gs** and an HTML file called **Index** from the teacher-only package; set `SPREADSHEET_ID` and, optionally, `TEACHER_EMAIL` in Code.gs.
3. Deploy → New deployment → Web app; Execute as **Me**; access as appropriate for students. Grant permissions. Copy the URL ending in `/exec`.
4. Edit this repository's `index.html`, replacing `PASTE_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE` with that URL.
5. GitHub repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
6. Visit `https://kellycur1991.github.io/P6-MathConceptition-Mock/` and test a submission, confirming the teacher's Google Sheet contains a saved row.

Until steps 1–4 are done, the site intentionally shows **Quiz setup required**. A publicly hosted static site cannot submit grades to Google Sheets by itself.

**Do not upload Code.gs, the answer key, student results, or the teacher-only backend ZIP to this public repository.** If your school's device policies block embedded Google Apps Script, share the Apps Script /exec URL with students directly.
