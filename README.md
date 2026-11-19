# FairTurn Play — classroom games & participation 🎓

**Version 2.0 — Arabic and English, free, offline-capable single HTML file**

FairTurn Play is an interactive classroom toolkit for teachers. It uses no paid APIs, servers, logins, or external libraries. Data is stored in your browser's local storage on the device you use. No student data is uploaded by the app. Use initials or nicknames if that better protects student privacy.

## What's new

1. **Participation** — fair random selection among present students with the fewest offered turns; animated reveal; record **Correct**, **Tried but incorrect**, or **Didn't answer**, with random kind feedback, optional audio, and celebration animations. Wrong answers count as an attempt, not a failed student.
2. **Team Challenge** — teacher chooses 2–12 teams, points for correct answers, and whether absent students are included. Randomized, as-balanced-as-possible team assignments; editable team names, manual student moves, adjustable scoreboard, random team picker, and reset confirmation.
3. **Random Quiz Arena** — 12 sample multiple-choice questions (Arabic and English) across math, science and language, plus custom teacher-entered four-option questions. Shuffle without repeats until the subject pool is exhausted, 15/30/60/90-second or unlimited timer, instant feedback for each attempt, reveal answer, and optional automatic award of team points for a correct answer. No paid AI or generation service is used.
4. **Original classroom features retained** — classes, students, attendance, fairness tracking, activity history, undo, CSV export, Arabic/English switching, and device-only persistence.

## Quick start

1. Extract the ZIP archive.
2. Open **index.html** in Safari, Chrome, or another up-to-date browser. For reliable persistent data, hosting it with GitHub Pages or another static host is recommended.
3. In **Participation**, add your students (one by one or as a list). You can also load eight sample students.
4. In **Teams & games**, choose the number of teams and press **Shuffle into teams**. Rename teams, move members, or adjust scores.
5. In **Random quizzes**, use the built-in sample questions or add your own. Pick a team to award points automatically for correct answers.

## Free GitHub Pages deployment (iPad, iPhone, or desktop)

1. Sign in to github.com and create a new **Public** repository called `fairturn-play` (or another name).
2. Open the repository, select **Add file → Upload files**. On an iPad/iPhone you may need Safari's **Request Desktop Website** to see the upload option.
3. Upload only **index.html** from the extracted folder and commit it to the `main` branch.
4. Go to **Settings → Pages → Build and deployment → Deploy from a branch**. Choose `main` and `/(root)`, then **Save**.
5. Your app URL will be `https://YOUR-USERNAME.github.io/fairturn-play/` if that is your repository name. The website is static and free to host on GitHub Pages.

## Notes

- **No student accounts**: the app is intended for teacher-operated use on one device. It does not sync automatically between devices. Browser private mode, storage cleaning, or a different device can remove local data.
- Use **Export report** for the original participation CSV. The team and quiz settings are local; CSV export does not yet include team scores or quiz performance.
- The built-in question set is a small demo aimed at introducing the experience; add age-appropriate course-specific questions before using it in a lesson.
- Audio defaults to off; animations respect operating-system reduced-motion preferences.
- Questions are local, fixed or authored by the teacher: “random quizzes” means shuffled from a question bank, **not** AI-generated.

## Files

- `index.html` — the complete self-contained web app
- `desktop-preview.png` — desktop view
- `mobile-preview.png` — team challenge on mobile
- `quiz-mobile-preview.png` — random quiz on mobile
- `team-desktop-preview.png` — populated teams view
