# Git & GitHub Crash Course

A tiny static website used for a Git and GitHub crash course. It demonstrates a minimal project that’s ideal for practicing common Git tasks (branching, commits, merges, PRs) without extra tooling.

## Overview
- Purpose: Provide a simple, no-build project for learning and demonstrating Git/GitHub workflows.
- App type: Static site (no JavaScript, no backend).
- Entry point: `index.html`.

## Tech Stack
- Languages: HTML5, CSS3
- Frameworks/Libraries: None
- Package manager / build system: None

## Requirements
- Any modern web browser (Chrome, Firefox, Edge, Safari).
- Optional: A simple static file server if you prefer not to open the HTML file directly from disk (examples below).

## Getting Started
You have two quick options to view the page locally:

1) Open directly in your browser
- Locate `index.html` in the project folder and open it (double-click or drag into a browser).

2) Serve via a simple local web server (optional)
Use any tool you already have installed. Examples:
- Python 3 (if installed)
  - PowerShell: `python -m http.server 8080`
  - Then visit: http://localhost:8080/
- PHP (if installed)
  - PowerShell: `php -S localhost:8080 -t .`
  - Then visit: http://localhost:8080/

Note: These commands must be run from the project root directory (where `index.html` resides).

## Scripts
There are currently no project scripts (no `package.json`, no build tools).
- TODO: If you add tooling later (e.g., npm, task runners), document the available scripts here.

## Environment Variables
None required.
- TODO: If future enhancements need configuration (e.g., analytics IDs), list and document env vars here.

## Tests
No tests are included in this repository.
- TODO: Consider adding basic checks such as HTML validation, CSS linting, or link checking. Document how to run them here.

## Project Structure
```
.
├── index.html   # Main HTML entry page
├── styles.css   # Styles for the page
├── logo.png     # Logo image referenced by index.html
└── README.md    # This documentation
```

## Known Limitations
- No JavaScript or dynamic behavior.
- No build step; assets are served as-is.

## License
No license file is currently provided.
- TODO: Choose and add a LICENSE (e.g., MIT, Apache-2.0, GPL-3.0) and update this section accordingly.
