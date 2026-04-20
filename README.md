# UTube — GitHub Pages Deployment

This branch contains the built static files served via GitHub Pages for the UTube web client demo.

## Live Demo

**https://avrhambi.github.io/Utube**

> Runs without a backend — videos, thumbnails, and profile images load from static files committed to this branch. Features requiring a backend (login, upload, comments) are not available in demo mode.

## What's in this branch

| Path | Description |
|------|-------------|
| `index.html` | React app entry point |
| `static/` | Compiled JS and CSS bundles |
| `public/media/images_new/` | Video thumbnail images |
| `public/media/videos_new/` | Video files |
| `public/media/Profile_Images/` | Author profile pictures |
| `videos.json` | Static video catalogue used as backend fallback |

## Full Project

The full source code (React client, Node.js server, C++ server, Android client) is in the `main` branch.
See the [main branch README](https://github.com/Avrhambi/Utube/tree/main) for the full project overview.
