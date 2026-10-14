# Throwaway Sample

A small practice application for two developers learning to work together with GitHub and Codex. The goal is to practice making changes, reviewing each other's work, and sharing clear project instructions.

## The application

Build a single page using plain HTML, JavaScript, and CSS. A user can:

- Enter an item in a text input.
- Add that item to a list using an **Add** button.
- Delete an individual item using a **Delete** button next to it.

Each delete button removes only its own item. Empty or whitespace-only input should not add an item. After adding an item, clear the input so the user can enter another one.

## Scope

Keep the application simple and easy to understand. Use plain HTML, JavaScript, and CSS without frameworks or a build step.

The first version does not need a backend, database, user accounts, or persistence. Items exist only while the page is open; refreshing the page resets the list.

## Project status

The project is at the documentation stage. The application has not been implemented yet.

## Planned files and local setup

- `index.html` — the page structure.
- `style.css` — the page styling.
- `script.js` — the logic for adding and deleting items.

Once these files exist, open `index.html` in a web browser to use the application. No package installation or build command is required.

## Working together

1. Agree on a small task in a GitHub issue, including what counts as complete.
2. Work on a separate branch for that task.
3. Use Codex to help implement, understand, and check the change.
4. Open a pull request explaining what changed and how it was checked.
5. Have the other developer review the change before merging it into `main`.

Keep changes focused on the agreed task. Record shared decisions in the issue or repository so both developers and their assistants can find them. Update this README when the scope or setup changes.

## Manual checks

Once the application is implemented, check it in a browser:

- Add one item and confirm it appears in the list and the input clears.
- Add several items and confirm they remain visible together.
- Delete a middle item and confirm the other items remain.
- Delete all items and confirm a new item can still be added.
- Try empty and whitespace-only input and confirm no item is added.
- Refresh the page and confirm the list resets.

## Purpose

This is a throwaway learning project. Success means both developers can make a small change, understand it, review it, and merge it using GitHub and Codex.
