# Loop Studio

A self-contained GIF editor. Version 2.1.0.

Open index.html directly or use the GitHub Pages site. GIF processing stays in the browser; there are no file uploads or server-side image processing. Named presets and theme preferences use local browser storage. Export presets to share or back them up.

Features include Gifsicle compression, resizing/cropping, frame editing and timing, live effects and captions, original/processed comparison, size estimates, saved presets, undo/redo, and mobile light/dark layouts.

## Source and licenses

[Download complete source and upstream source archives](Loop-Studio-source.zip). The source package includes build instructions, pinned dependencies, tests, validation notes, and upstream licenses. Editor code and Gifsicle are GPL-2.0-or-later; other bundled libraries retain their upstream licenses. See LICENSE and the editor’s Guide.

## Publishing

In Settings → Pages, use Deploy from a branch, main, and / (root). The .nojekyll file serves the self-contained HTML without Jekyll processing.
