MIS Khasra Search - Single-file static website
---------------------------------------------
Files:
- index.html : main UI
- data.json  : exported data (from your Excel)

How to use locally:
1. Unzip the package.
2. Open index.html in a browser (Chrome/Edge/Firefox). If the browser blocks fetch of local file, you can:
   - Serve using a simple local server:
     python3 -m http.server 8000
   - Then open http://localhost:8000 in browser.

How to host for free:
- GitHub Pages: create a repo, push these files to the repo root, enable Pages.
- Netlify / Vercel: drag-and-drop the folder, site will be published.

PDF:
- Use browser Print -> Save as PDF to download details.

Note:
- This is a static client-side app. No coding required to run. To update data, replace data.json.
