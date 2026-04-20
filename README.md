# UTube

UTube is a full-featured video-sharing application modeled after YouTube, developed as part of an Advanced System Programming course at Bar-Ilan University.

## Overview

The project features a dual-server architecture — a Node.js server for core functionality and a C++ server for intelligent content recommendations — along with web and Android client applications.

**Components:**

| Folder | Description |
|--------|-------------|
| [`C++_server/`](./C++_server/) | C++ TCP server for video recommendations |
| [`Node-js_server/`](./Node-js_server/) | Node.js REST API — users, videos, auth, comments |
| [`Web_client/`](./Web_client/) | React web frontend |
| [`Android_client/`](./Android_client/) | Native Android app |

---

## Visit the App — Demo Mode

A live static demo of the web client is hosted on GitHub Pages. It runs without a backend; videos and thumbnails load from static files.

**https://avrhambi.github.io/Utube**

> Note: Features that require a backend (login, upload, comments) are not available in demo mode.

---

## Wiki — Full Documentation

For complete setup guides, API documentation, architecture diagrams, and screenshots, visit the **[Wiki tab](https://github.com/Avrhambi/Utube/wiki)**.

---

## Quick Start (Full Stack)

1. **C++ server** — build and run first (see [`C++_server/README.md`](./C++_server/README.md))
2. **Node.js server** — install dependencies and start (see [`Node-js_server/README.md`](./Node-js_server/README.md))
3. **Web client** — `npm install && npm start` (see [`Web_client/README.md`](./Web_client/README.md))
4. **Android client** — open in Android Studio (see [`Android_client/README.md`](./Android_client/README.md))
