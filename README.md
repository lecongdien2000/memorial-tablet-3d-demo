# Memorial Tablet 3D Demo

A tiny **client-side-only** Three.js demo.

## What it does

- Shows a simple Asian-style memorial tablet made from Three.js geometry
- Drag to rotate the camera around the model
- Scroll / pinch to zoom
- No database
- No backend
- No React
- No Node.js build step
- Suitable for GitHub Pages

## Files

```text
memorial-tablet-3d-demo/
├── index.html
└── README.md
```

## Run online with GitHub Pages

1. Create a new GitHub repository, for example:
   `memorial-tablet-3d-demo`
2. Upload `index.html` and `README.md` to the repository root.
3. In GitHub, open:
   **Settings → Pages**
4. Under **Build and deployment**, choose:
   **Deploy from a branch**
5. Select:
   - Branch: `main`
   - Folder: `/ (root)`
6. Save.
7. GitHub will give you a public URL similar to:
   `https://YOUR-USERNAME.github.io/memorial-tablet-3d-demo/`

That link can be opened on a phone or computer.

## Why this version is intentionally simple

This first demo tests only the most important idea:

> Can the customer open a normal web link and rotate a 3D memorial tablet?

Once that works, the next version can replace the procedural demo tablet with a real `.glb` model exported from Blender.

## Technology

- HTML
- CSS
- JavaScript
- Three.js
- OrbitControls
- jsDelivr CDN

Everything runs in the browser.
