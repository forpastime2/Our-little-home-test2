# Our Little Home — prototype

## Included
- `index.html`: responsive single-screen room UI
- `manifest.json`: PWA manifest
- `sw.js`: basic offline cache
- `icon.svg`: app icon

## Publish on GitHub Pages
1. Extract the ZIP.
2. Upload the files and folders inside this directory to the root of your GitHub repository (not the ZIP itself).
3. In repository Settings → Pages, choose `Deploy from a branch`, branch `main`, folder `/(root)`, and Save.
4. Open the URL shown on the Pages settings page. On iPhone use Safari → Share → Add to Home Screen. On Android use Chrome → menu → Add to Home screen / Install app.

## Important prototype limitations
This version stores data in the current browser using localStorage. The password is a local demo gate, not secure authentication. Chat is a local demo, not real-time or cross-device. For a shared two-person production app, connect a free-tier backend such as Supabase for authentication, database, realtime, storage, and server-side Row Level Security. Free plans have quotas and terms that may change; avoid storing irreplaceable photos without a backup.
