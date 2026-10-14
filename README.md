# Throwaway Sample v2

A small practice application for two developers learning to work together with GitHub and Codex. The goal is to practice making changes, reviewing each other's work, and sharing clear project instructions.

## The application

Build a single page using plain HTML, JavaScript, and CSS. A user can:

- Enter an item in a text input.
- Enter optional details in a second text input stacked below the first.
- Add that item to a list using an **Add** button.
- Delete an individual item using a **Delete** button next to it.

Each delete button removes only its own item. An empty or whitespace-only item should not be added. Show the optional details below the item text in the same list entry. After adding an item, clear both inputs so the user can enter another one.

## Scope

Keep the application simple and easy to understand. Use plain HTML, JavaScript, and CSS without frameworks or a build step.

The first version does not need a backend, database, or user accounts. Items and their optional details are saved in browser local storage and survive a refresh in the same browser. They are not shared between browsers or devices. Items saved before the details feature continue to load.

## Project status

The first version is implemented as a single `index.html` file with fewer than 100 lines.

## Files and local setup

- `index.html` — the page structure, styling, and add/delete logic.

Open `index.html` in a web browser to use the application. No package installation or build command is required. Browser storage must be enabled for items to persist. Use the same file location and browser to return to your list.

## Working together

1. Agree on a small task in a GitHub issue, including what counts as complete.
2. Work on a separate branch for that task.
3. Use Codex to help implement, understand, and check the change.
4. Open a pull request explaining what changed and how it was checked.
5. Have the other developer review the change before merging it into `main`.

Keep changes focused on the agreed task. Record shared decisions in the issue or repository so both developers and their assistants can find them. Update this README when the scope or setup changes.

## Manual checks

Check the application in a browser:

- Add one item and confirm it appears in the list and the input clears.
- Add an item with details and confirm both lines appear in the same list entry and both inputs clear.
- Add an item without details and confirm it works as before.
- Enter only details with an empty or whitespace-only item and confirm nothing is added.
- Add several items and confirm they remain visible together.
- Delete a middle item and confirm the other items remain.
- Delete all items and confirm a new item can still be added.
- Try empty and whitespace-only input and confirm no item is added.
- Refresh the page and confirm the remaining items are still present.
- Refresh after adding an item with details and confirm both lines are still present.
- Delete an item, refresh, and confirm it stays deleted.
- Delete an item with details and confirm both lines are removed together and stay removed after a refresh.

## Purpose

This is a throwaway learning project. Success means both developers can make a small change, understand it, review it, and merge it using GitHub and Codex.
