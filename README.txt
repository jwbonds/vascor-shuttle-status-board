VASCOR Transport Shuttle Status Board Web App

Files:
- display.html: TV/display page
- admin.html: dispatcher/admin page
- boarddata.json: shared data file
- logo.png: VASCOR logo

How it works:
1. Host all files in the same folder on GitHub Pages, Netlify, Vercel, or another web host.
2. TV opens display.html.
3. Dispatcher opens admin.html.
4. Dispatcher edits data and clicks Download boarddata.json.
5. Replace/upload boarddata.json on the host.
6. display.html checks boarddata.json every 10 seconds and updates automatically.

Note:
This version is static-hosting friendly. A browser-only static page cannot directly save to the web host without a backend/API.
