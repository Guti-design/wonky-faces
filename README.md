# Wonky Faces

**Wonky Faces** is a browser-based warp tool for artists who want to create funny, distorted character references without learning Photoshop.

Designed by **Shom**.

![Wonky Faces editor preview](screenshots/editor-preview.png)

## What it does

- Distorts an image with a connected **4-column × 5-row** warp grid.
- Drag individual grid points or line segments; neighbouring geometry stays connected.
- Includes a sample face, image upload, drag-and-drop, canvas colour picker, grid colour picker, and canvas formats.
- Supports 4:5, 9:16, 1:1, 16:9, 4:3, and window formats.
- Includes Sculpt and Loop Preview modes.
- Records only the artwork canvas, so the editing grid, handles, panel, and cursor are excluded.
- Adds a smooth return to the opening frame for a seamless loop.
- Saves a supported MP4 or WebM recording to your browser’s Downloads folder.

![Warped face preview](screenshots/warped-preview.png)

## Open it

Double-click `index.html`. It works as a standalone file with no install, server, library, or build step.

## Controls

- **Drag a dot** to move one grid point.
- **Drag a line** to move both connected points.
- **Space** — pause/play.
- **V** — start recording.
- **S** — finish and save the loop, or download the last recording again.
- **H** — hide/show the control panel.
- Use **Reset** to return to the sample face and default settings.

For best recording support, use a current Chrome, Edge, or Firefox browser. The browser decides whether the downloaded file is MP4 or WebM.
