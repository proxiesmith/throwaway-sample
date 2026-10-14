# Project roadmap

## What we are trying to do

Build a small list application while learning how two developers can work together using GitHub and Codex. The aim is to practice agreeing on tasks, making clear changes, reviewing each other's work, and merging those changes into `main`.

Keep the application simple: use plain HTML, CSS, and JavaScript without frameworks or a build step. The first version needs no backend, database, user accounts, or persistence.

## Roadmap

1. **Agree on the project scope.** Document the application requirements and shared decisions. This stage is complete; the application has not been implemented yet.
2. **Build the page.** Create `index.html`, `style.css`, and `script.js`, with a text input, an Add button, and a list of items.
3. **Implement the list behavior.** Add nonblank items, clear the input after adding, and let each Delete button remove only its own item. Items remain only while the page is open.
4. **Check the application.** Follow the manual checks in the [README](../README.md): add several items, delete individual items and all items, reject empty or whitespace-only input, and confirm that refreshing resets the list.
5. **Review and merge the work.** Split implementation into small GitHub issues with clear completion criteria. Use a separate branch for each task, make focused commits with descriptive messages, and have the other developer review each pull request before merging into `main`.

## What success looks like

The page works by opening `index.html` in a browser, and both developers can explain, check, review, and merge a small change. Keep the [README](../README.md) and [shared decisions](decisions.md) current as the project develops.
