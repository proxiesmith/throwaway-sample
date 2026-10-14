# Project roadmap

## What we are trying to do

Build a small list application while learning how two developers can work together using GitHub and Codex. The aim is to practice agreeing on tasks, making clear changes, reviewing each other's work, and merging those changes into `main`.

Keep the application simple: use plain HTML, CSS, and JavaScript without frameworks or a build step. The first version needs no backend, database, or user accounts. Save items in browser local storage.

## Roadmap

1. **Agree on the project scope.** Document the application requirements and shared decisions. This stage is complete; see Decisions 002 and 003 for the single-page app and optional details requirements.
2. **Build the page.** Implemented in one 94-line `index.html` file containing HTML, CSS, and JavaScript, a required item input, an optional details input, an Add button, and a list of items.
3. **Implement the list behavior.** Implemented: add nonblank items with optional details, clear both inputs, and delete an item and its details together. Browser local storage preserves changes across refreshes and loads items saved before the details feature.
4. **Check the application.** Follow the manual checks in the [README](../README.md): add items with and without details, reject blank items even when details are supplied, delete individual items and all items, and confirm that refreshing preserves additions, details, and deletions.
5. **Review and merge the work.** Split implementation into small GitHub issues with clear completion criteria. Use a separate branch for each task, make focused commits with descriptive messages, and have the other developer review each pull request before merging into `main`.
6. **Apply a minimalist red theme (planned).** Use a simple layout, generous spacing, and red accents for buttons and interactive states. Keep text readable, maintain clear keyboard focus indicators, and preserve the existing functionality and single-file limit of fewer than 100 lines.
7. **Publish with GitHub Pages.** Publish static files from the root of `main` and verify the app at [the live URL](https://proxiesmith.github.io/throwaway-sample/). Future merges to `main` deploy automatically; use the repository's Actions tab to check deployment status.

## What success looks like

The page works by opening `index.html` in a browser, and both developers can explain, check, review, and merge a small change. Keep the [README](../README.md) and [shared decisions](decisions.md) current as the project develops.
