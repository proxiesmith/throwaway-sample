# Project decisions

This file records agreed decisions for both developers and their Codex assistants. Update it when the team agrees to change a decision.

## Decision 001: Keep the technology and commits simple

- **Date:** 2026-10-14
- **Status:** Accepted

### Decision

- Use only plain HTML, CSS, and JavaScript.
- Do not use frameworks.
- Keep commits small and focused on one logical change.
- Write descriptive commit messages that explain what changed.

### Reason

This is a simple throwaway application for practicing collaboration with GitHub and Codex. A minimal technology stack keeps the code easy to understand. Small, focused commits with descriptive messages make changes easier to review and discuss.

### Examples of commit messages

- `Add input and button for creating list items`
- `Add delete button to each list item`
- `Prevent adding empty list items`

## Decision 002: A single page with browser storage

- **Date:** 2026-10-14
- **Status:** Accepted

### Decision

- Keep the application in one `index.html` file containing HTML, CSS, and JavaScript, with fewer than 100 lines.
- Save list items in browser local storage so additions and deletions survive a refresh.

### Reason

The requested first version should be easy to open and inspect while retaining the user's list. This replaces the original plan for separate files and a list that resets on refresh. No framework or backend is needed.
