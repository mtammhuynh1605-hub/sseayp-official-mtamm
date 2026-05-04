CULTURE PASSPORT ASEAN-JAPAN - NETLIFY STATIC DEPLOY

This folder is the deployment-ready version for Netlify.
It contains only static files: index.html, assets/, netlify.toml, and _redirects.
There is NO package.json and NO npm workspace, so Netlify will not run npm install.

Option 1 - easiest drag-and-drop deploy:
1. Open Netlify.
2. Go to Add new site > Deploy manually.
3. Drag this entire folder OR drag the ZIP file culture-passport-netlify-static.zip.
4. Netlify will publish the website directly.

Option 2 - GitHub deploy:
1. Upload all files in this folder to the root of a new GitHub repo.
2. In Netlify, choose Import from Git.
3. Build command: leave empty.
4. Publish directory: .
5. Deploy.

Important:
- Do not upload the previous full React/Express workspace folder if you only want a simple Netlify frontend deploy.
- This static version keeps the same frontend content and visual design.
- Backend/AI features run in demo/local-preview mode in this static version. For real AI calls, use a serverless function or deploy the backend separately.
