# AGENTS.md

## Cursor Cloud specific instructions

This is a **zero-dependency static HTML/CSS/JS portfolio website**. There is no build system, no package manager, no test framework, and no linting configuration.

### Running the dev server

Serve the site with any static HTTP server from the repository root:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in a browser. All pages are plain `.html` files (`index.html` + 13 pages under `pages/`).

### Key caveats

- **No build step**: Files are served as-is; there is nothing to compile or bundle.
- **No automated tests or linting**: The project has no `package.json`, test runner, or linter config. Validation is manual/visual only.
- **Google Fonts dependency**: The site loads Sora and DM Sans from `fonts.googleapis.com`. Internet access is required for correct font rendering.
- **Images**: All image assets live under `images/` with subdirectories for specific projects (`art/`, `joyrun/`, `mindflux/`, `referlink/`, `tinycloset/`).
- **Content editing**: `CONTENT.md` is the master content reference file; it documents the text on every page.
