# CampusNotes

CampusNotes is a lightweight study-notes manager built with HTML, CSS, and vanilla JavaScript. It runs directly in a modern browser and does not require a package installation or build step.

## Features

- Create, edit, and delete study notes
- Search note titles, subjects, tags, and content
- Filter notes by subject and sort the list
- Pin important notes
- Save notes in browser Local Storage
- Responsive layout for desktop and mobile screens

## Run the project

1. Extract the project folder.
2. Open `index.html` in a modern web browser.
3. Select **New note** to add a note. Changes are saved in the current browser.

No server or dependency installation is required.

## Project files

- `index.html` — page structure and note editor
- `styles.css` — responsive styles
- `app.js` — note management, search, filtering, and browser storage
- `.gitignore` — common temporary and backup files to ignore

## Data storage note

Notes are stored locally in the browser under the key `campusnotes-v1`. They do not sync between browsers or devices. Clearing browser site data may remove saved notes.

## Version control

This folder intentionally does not include a `.git` directory. Initialize Git in the extracted folder and connect it to your own GitHub repository.
