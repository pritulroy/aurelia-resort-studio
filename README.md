AURELIA — Modern Luxury Resort Design Studio

A free, browser-based conceptual design studio: an interactive 3D resort, ten coordinated architectural drawings, parametric editing, project save/load, GLB and drawing export, a cinematic film mode and a presentation mode.

Built by Pritul Roy — https://pritulroy.github.io/pritul-portfolio/

Conceptual design only. Not for construction. It has not been checked against building codes, setbacks, accessibility, fire egress, structure, foundations, services or environmental design. Interior layouts are proposed and are not modelled in 3D.

Technology

HTML5, CSS3, JavaScript ES modules, Three.js 0.160.0 (loaded from the jsDelivr CDN, so an internet connection is required), SVG. No backend, no build tools, no paid services.

Run it on Windows
Install VS Code and the Live Server extension (Ritwick Dey).
Put all the project files in one folder, for example aurelia.
Open the folder in VS Code, right-click index.html, choose Open with Live Server.
Do not double-click index.html: browsers block ES modules from file://.
Files
index.html is the active application.
index.phase1.html, index.phase2.html, index.phase3-batch1.html, index.phase3-batch2.html, index.phase3-complete.html are earlier backups.
index.phase4-complete.html is a copy of the final version.
Using it
3D view: drag to orbit, right-drag to pan, scroll to zoom, click an object to inspect it. Toolbar buttons give camera views, Day / Golden hour / Night, Save image and Auto-orbit.
Drawings: the Drawings button opens ten drawings (site plan, ground, typical and roof plans, four elevations, two sections). Wheel to zoom, drag to pan, Fit / reset. Export SVG saves the current drawing, Export all (ZIP) saves all ten, Print / PDF opens the print dialog (choose Save as PDF). Scales are illustrative, not exact print scales.
Design parameters (left panel): hotel floors (2–5), floor height, balcony depth, pool length and width, site width and depth, landscape density. Press Apply parameters. Invalid values are rejected with a message and the last valid design is kept. Hotel width, depth and room bay are shown but locked, because the interior plans are keyed to them.
Project: Save downloads AURELIA_Project.json; Load validates and restores it; the design autosaves in your browser; Reset restores defaults and clears autosave. Export GLB saves the visible 3D scene for Blender or other viewers. The sky, animated water ripples, shadows and environment reflections are not exported. Screenshot 1080p saves a clean PNG.
Cinematic studio: tick the shots you want, set seconds per shot, optional hold and sun cycle, then Play, Pause/Resume, Stop or Preview.
Video recording: choose 720p or 1080p and 24 or 30 fps, then Start recording. With Record whole tour ticked it plays the tour and stops by itself. Keep the browser tab visible. The file is WebM; convert to MP4 with VLC (Media → Convert) or HandBrake if you need MP4. Audio is not supported.
Present: full-screen mode with the project panel, shot buttons and lighting. Esc exits.
Quality: Low, Balanced or High changes shadow resolution and pixel ratio. Use Low on integrated graphics.
Browser support

Chrome and Edge are recommended. Firefox works for most features. Safari has limited MediaRecorder support, so recording may be unavailable.

Known limitations
The camera tour does not avoid clipping through objects.
Levels 3 and above use a proposed room grid that is clipped to the stepped floor outline.
Hotel width, depth and room bay are not editable.
Tree positions are fixed; landscape density only shows or hides trees.
