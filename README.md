# Rocky's Lassi Palace Website (Frontend)

This is a standalone React + Vite website. It does not require `server/index.js` or a separate Node backend to start the frontend.

## Run locally
1. Extract this ZIP into a NEW folder, for example `C:\Users\sivam\Downloads\rockys-lassi-palace-correct`.
2. Open that exact folder in VS Code (the folder containing `package.json`).
3. Open Terminal in VS Code and run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the `Local` URL printed by Vite, usually `http://localhost:5173/`.

## Build for Cloudflare Pages
Run `npm run build`. Upload/connect this folder to Cloudflare Pages with build command `npm run build` and output directory `dist`.

## Important
- This is the frontend version. Cart orders are stored in this browser's local storage only; they are not automatically sent to the shop or shared across devices.
- WhatsApp ordering opens a WhatsApp message to the configured shop number in `src/App.tsx`.
- Store Dashboard demo PIN is `1234`. This frontend-only PIN is not secure for a public live site. Add a backend with server-side authentication before using real customer order data.
- Menu items/prices and stock images should be verified/updated by the shop before publishing.
