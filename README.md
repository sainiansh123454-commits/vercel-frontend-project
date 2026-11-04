# TraceLab — Forensic Science Explorer

Responsive React + Vite frontend with:
- Overview dashboard and learning statistics
- Searchable/filterable forensic science learning library
- Save/unsave module interactions
- Module detail popup
- Sample case studies page
- Mobile responsive navigation

## Run locally
1. Install Node.js (LTS).
2. Open this folder in VS Code or a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown in your terminal.

## Build
Run `npm run build`. Vite creates the production files in `dist/`.

## Deploy on Vercel
1. Create a **public** GitHub repository named `forensic-lab-explorer`.
2. Upload/push all project files (do not upload `node_modules`).
3. In Vercel, choose **Add New → Project** and import that GitHub repository.
4. Framework Preset: **Vite**
5. Build Command: `npm run build`
6. Output Directory: `dist`
7. Click **Deploy**, then open the generated `.vercel.app` link and test navigation, search, filters, save buttons and module popups.

No environment variables are needed.

## Submission template
Live Deployment: https://YOUR-PROJECT-NAME.vercel.app
GitHub Repository: https://github.com/YOUR-USERNAME/forensic-lab-explorer

Replace placeholders with your actual public links after deployment.
