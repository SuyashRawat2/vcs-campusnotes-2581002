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
## Contribution Workflow

Contributors can improve CampusNotes by following these steps:

1. Fork the repository on GitHub.
2. Clone your fork to the local system.
3. Add the original repository as an upstream remote.
4. Create a separate feature branch for each improvement.
5. Make the required changes and test them.
6. Commit changes using Conventional Commit messages.
7. Push the feature branch to GitHub.
8. Open a Pull Request against the original repository's main branch.

## Commit Message Convention

Use the following format:

type: short description

Examples:
- feat: add new notes functionality
- fix: resolve note validation issue
- docs: improve project documentation
## Contribution Workflow

1. Fork the repository on GitHub.
2. Clone your fork locally.
3. Add the original repository as upstream:

   git remote add upstream https://github.com/OWNER/REPOSITORY.git

4. Create a feature branch.
5. Make changes and test the application.
6. Commit using Conventional Commit messages.
7. Push your feature branch.
8. Open a Pull Request.

## Manual Testing

- Create a new note.
- Search for a note by title.
- Filter notes by subject.
- Pin and unpin notes.
- Edit and delete notes.
- Refresh the browser and verify saved notes.

## Conventional Commit Examples

- feat: add notes functionality
- fix: resolve validation issue
- docs: update documentation
- refactor: simplify note rendering
- chore: update project configuration