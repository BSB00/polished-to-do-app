# Daylight To-do

A lightweight task manager that runs directly in your browser. It is built as a single HTML file with no server, framework, or dependencies.

## Getting started

Open `index.html` in a browser. Your tasks are saved automatically in the browser's `localStorage`, so they remain available when you return using the same browser.

## Features

- Add tasks, mark them complete, or delete them.
- Filter the list to show all, active, or completed tasks.
- Clear all completed tasks at once.
- Start with three example tasks on the first visit.
- Adapt to your system's light or dark color theme.
- Respect reduced-motion preferences.
- Use the app on narrow screens as well as desktop.

## How it works

The interface and behavior are contained in `index.html`:

- **HTML** provides the accessible task-list structure.
- **CSS** handles layout, themes, and checkbox animations.
- **Vanilla JavaScript** manages task interactions and persistence.

Tasks are stored under the `daylight-tasks-v1` key in `localStorage`. The example tasks appear when no saved list exists yet.
