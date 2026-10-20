# Git Playground

An interactive, browser-based playground for learning essential Git commands and workflows through guided lessons and a simulated terminal.

## Overview

Git Playground is a small learning project built with HTML, CSS, and vanilla JavaScript. It helps beginners explore common Git workflows without installing Git or working in a real repository.

The terminal **simulates** supported commands; it does not execute Git commands on your computer or interact with GitHub.

## Features

- Eight guided lessons covering `git init`, `git status`, `git add`, `git commit`, `git log`, branching, merging, and remote workflows
- Interactive command input with command history and hints
- Lesson tasks and completion tracking during the current session
- Visualizations of working, staging, local, and remote areas
- Commit history and branch visualization
- Runs directly in a browser without a build step

## Getting started

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Follow the lessons and enter commands in the simulated terminal.

No dependencies, installation, or backend server are required. The page uses Google Fonts, so typography may look different when offline.

## How to use

Start with **`git init`**, then follow the lesson tasks. Use **Terminal** to enter commands and **Visualization** to see how the simulated repository changes. Type `help` to see the supported command families or `clear` to clear terminal output.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript

## Known limitations

- **Lesson skipping / command validation:** Navigating directly to the `git commit` lesson can allow a commit to succeed before `git init` has been run. This behavior is a known bug in the original version.
- The terminal is a teaching simulation, not a complete Git parser or a substitute for real Git.
- Command behavior depends on the selected lesson; some commands are not supported across all lessons.
- Progress and simulated state are not persisted across page reloads.
- The interface is primarily designed for desktop use; on narrower screens, the lesson sidebar is hidden.

## Future improvements

Possible future refinements include more consistent command validation, clearer navigation on mobile, and more realistic repository-state checks. These are ideas, not planned features.

## Project status

A small portfolio/learning project shared in its current form. No active feature expansion is planned.

## License

No license has been added yet. All rights are reserved by default until the author selects a license.
