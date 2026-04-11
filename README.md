# App Support Pages

This repository hosts a shared GitHub Pages support site for multiple apps.

## Structure

- `/` is the landing page where users select an app.
- `/sudoku/` contains the Sudoku365 Classic support pages.
- `/calculator/` contains the calculator support pages.
- `/shared/` contains assets used across multiple app pages.

## Adding Another App

1. Create a new app folder at the repository root, for example `/weather/`.
2. Add that app's `index.html`, `faq/`, `privacy/`, and any app-specific assets.
3. Add one more `.app-card` entry in `/index.html`.
4. Add a matching icon file in `/shared/icons/`.

## Reporting Bugs

If you encounter a problem with any app listed here, open a GitHub issue in this repository and include the app name,
app version, device, OS version, reproduction steps, and screenshots when relevant.
