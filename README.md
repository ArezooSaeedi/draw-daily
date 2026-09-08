# Draw Daily

An iPad-first drawing-practice web app. It is intentionally framework-free, so you can learn from the code without a build system getting in the way.

## What is included

- Apple Pencil and touch drawing, including Pencil pressure
- Pen, eraser, color, brush size, undo, redo, and clear controls
- Four starter exercises: lines, ellipses, boxes, and shading
- Automatic draft saving and a local drawing gallery
- A simple practice timer
- An installable, offline-friendly web-app manifest

## Run it

Put this folder behind any static web host, then open it in Safari on your iPad. A simple choice is GitHub Pages, Netlify, or Vercel. Once it is open in Safari, use **Share → Add to Home Screen** to install it like an app.

For local testing on a computer, run any static-file server from this folder and visit the address it gives you. Serve it over your local network to open the same address on the iPad.

## Where to explore next

- `index.html` defines the app’s screens and controls.
- `styles.css` controls the iPad-first layout and visual design.
- `app.js` contains the drawing engine, exercises, local saving, gallery, and timer.

The next meaningful upgrades would be custom exercise packs, an opacity control, exporting a drawing to Photos, and optional cloud sync.
