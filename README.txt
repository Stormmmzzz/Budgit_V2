Budgit — minimalist subscription and savings tracker

Files
- index.html: app structure
- script.js: app logic and local data
- sty.css: styling and responsive layout

Run
1. Extract this folder.
2. Open index.html directly, or use VS Code Live Server.
3. Data is stored locally in this browser. Back up your browser data before clearing site storage.

Features in this update
- Minimalist UI with a darker #69d620 green accent and a black Decide hero.
- Subscription logos: preset brand marks, uploaded images, and a live selection preview. Uploaded images are stored in browser local storage as compressed data URLs.
- Savings goals and repeating savings habits; log saved/spent amounts any time; check-in prompts can run while the app is open at the selected time.
- Daily/weekly/monthly savings guidance for goals with a target date.
- Dark theme colors across cards, forms, navigation, and modals.
- Settings credit: Created by Stephan Ngenda.

Font note
The stylesheet requests Nexa Pro by local font name. Nexa Pro is a licensed font and is not bundled. Install the licensed Nexa Pro font on the device, or provide the licensed .woff2/.woff font files and add them to the project to guarantee the exact typeface across devices.

Currency note
Subscription prices retain their original currency and totals convert into the selected default currency using Frankfurter exchange rates when available. Internet access is needed for fresh rates.

Reminder note
Browser timers only run while the app tab is open. The savings check-in will not pop up when the browser is fully closed.


NEXA PRO FONT
The Nexa Pro and Nexa Text Pro variable font files are included in ./fonts and loaded locally by sty.css, so no Google Fonts connection is required.
The supplied font archive identifies the fonts as Demo / Trial. Review its licensing terms and obtain a suitable licence before commercial distribution.
