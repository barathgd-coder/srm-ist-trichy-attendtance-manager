# Attendance Compass
https://barathgd-coder.github.io/srm-ist-trichy-attendtance-manager/
Attendance calculator, OD simulator and Attendance Advisor chatbot for SRM IST Tiruchirappalli (odd semester 2026-27).

## Run in VS Code
1. Unzip and open the folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension.
3. Right-click `index.html` > "Open with Live Server".
   (Or just double-click `index.html`; no build step or internet-only backend needed. Google Fonts need internet, otherwise a fallback font is used.)

## Files
- `index.html`  page structure
- `style.css`   styling
- `app.js`      timetable data (`SECTIONS`), calculations, charts, OD simulator, chatbot

## Things to edit
- Semester dates and holidays: in the page under "Semester dates and holidays", or the defaults in `st` at the top of the state section in `app.js` (`start`, `end`, `holidays`).
- Add a section: copy an entry in `SECTIONS` in `app.js` and change its subjects and timetable grid (`.` = free period, letters = subject slots, `L` = lab).

## Deploy (for the final live link)
Drag the folder onto https://app.netlify.com/drop, or push to GitHub and enable GitHub Pages.
