# housereset
House Reset

A one-page cleaning and organizing checklist for the week of Oct 27 to Nov 1, 2026. It covers the laundry room, master bedroom, dining room and kitchen, living room, Miles' room, the girls' room, and three bathrooms.

Features
Day-by-day plan with tasks grouped into timed blocks
Check off tasks as you go, with progress for each block, each day, and the whole week
Floating sprint timer (10, 25, or 45 minutes) that can be minimized
Guide tab with sorting rules (Keep, Storage, Donate, Trash) and a list of what moved to after Nov 2
Black and white design with light and dark modes

Files
index.html: the entire app (HTML, CSS, and JavaScript in one file)

Deploy to GitHub Pages
Create a new repository and upload index.html to the top level.
Open Settings, then Pages.
Under Build and deployment, set Source to Deploy from a branch.
Choose the main branch and the / (root) folder, then save.
Wait a minute or two. The site appears at https://<username>.github.io/<repository>/.

Notes
Progress is saved in the browser on the device you use. It does not sync between devices, and clearing the browser's site data resets it.
To change the schedule, edit the DAYS list near the top of the script in index.html. Each day holds blocks, and each block holds tasks.
Fonts (Geist and Geist Mono) load from Google Fonts. Without a connection the page falls back to system fonts.
No build step and no dependencies.