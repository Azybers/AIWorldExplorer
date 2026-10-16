# AI World Explorer — starter project

This is the first front-end prototype for the AI World Explorer website/PWA.

## Included
- Responsive, minimal mobile-friendly interface
- English / Filipino text switching
- Image selection and preview
- Save photos and notes in the current browser using local storage
- Remove saved items
- Basic PWA manifest and offline service worker

## Important current limitations
This is a **front-end starter**, not yet the complete public AI app:
- AI image recognition is not connected. It does not identify species or objects yet.
- Sign-in, user accounts, database sync, and public sharing are not connected.
- Saved pictures are stored only in this browser on this device. Clearing browser data can delete them.
- Browser storage has limits; this prototype compresses images to help.
- It does not identify a person's real-world identity from their face.

## How to preview
Open `index.html` in a modern browser. For service-worker/PWA testing, serve this folder over HTTPS or localhost rather than opening the file directly.

## Suggested next development stage
1. Deploy this front end to a static host.
2. Add a server-side API endpoint for image analysis. Keep API keys on the server; never put secret API keys in `app.js`.
3. Connect a database and authentication (for example, a free-tier backend).
4. Add per-user private collections, upload limits, privacy policy, and abuse protection.
5. Package the PWA/web project for Android after the web version works.

## Cost note
Free-tier services have usage limits and terms that can change. Public AI inference is often the part most likely to require a paid plan as usage grows.
