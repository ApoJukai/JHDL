# John Harley De Leon Portfolio

## Direct offline preview
Open `dist/index.html` directly in a browser. The production build uses relative paths and works from an extracted folder.

## Netlify deployment
Upload the whole project to GitHub and import it in Netlify. Settings are already included in `netlify.toml`:
- Build command: `npm run build`
- Publish directory: `dist`
- Node version: `22`

Alternatively, drag the prebuilt `dist` folder into Netlify Drop.

## Local development
```bash
npm install
npm run dev
```

## Personal assets
- Add `public/profile2.png`. A fallback image is already included.
- Add `public/John-Harley-De-Leon-CV.pdf` for the CV button.
- Replace the placeholder LinkedIn URL in `src/App.jsx`.
