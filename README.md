# ProtoMind

ProtoMind is a browser-based prototype-planning MVP for arranging example hardware components in an isometric scene.

## Run locally

Open `index.html` in a modern browser. No build step, package installation, or backend is required. Scene edits are saved in that browser's local storage.

## GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to its root. Keep `index.html` at the repository root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select the `main` branch and `/ (root)` and save.
4. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages settings.

## MVP features

- Overview dashboard and Autonomous Rover project
- Component library with search and category filters
- Add, select, drag, rotate, remove, and undo component changes
- Example compatibility warnings based on the specifications shown in the interface
- Demo Engineer chat with a component suggestion that can update the scene
- Local browser persistence and JSON specification export

## Demo and engineering limits

The scene is an illustrative 2.5D view, not a CAD model. Chat replies are local demo logic; no AI service is connected. Component specifications and compatibility rules are examples and have not been checked against current manufacturer datasheets. The app does not validate wiring, mechanical fit, thermal behavior, battery safety, or real-world operation. Treat every design as **simulation only**, and independently verify parts and designs before building.

The interface loads DM Sans and DM Mono from Google Fonts when an internet connection is available; system font fallbacks are included.
