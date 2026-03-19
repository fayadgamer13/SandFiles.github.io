# SandFile

SandFile is a single-file client-side web app to preview local project files. It lets you upload a folder (via directory picker) or drop files, browse the file tree, and preview many file types including HTML (live view), images, video, audio, and text/code. The UI follows a Material You–inspired aesthetic with accent color support and simple animations.

Features
- Upload folder (directory picker) or drop files.
- File tree with emoji icons for file types and folders.
- Preview: HTML live view (renders in iframe), text and code, images, audio, video.
- Download selected file, open preview in a new window, fullscreen preview.
- Material You inspired UI, accent color picker, dark-mode toggle.
- Entirely client-side; no server required.

Limitations
- ZIP extraction is not bundled in this single-file demo. For ZIPs, extract locally or provide a library (e.g., fflate or JSZip) and wire the unzip logic into the zipPicker handler.
- Relative asset loading in HTML previews may be limited — embedded server-like mapping of relative paths requires a more advanced in-browser routing approach or service worker.

Usage
1. Save `sandfile.html` and open it in a modern browser.
2. Click "Open folder" and choose a project folder, or drag-and-drop files into the window.
3. Select files from the tree or right pane to preview.
4. For HTML files, click "Load" or "Load live HTML" to render the page.

License
This example code is provided as-is for demonstration and development use.

