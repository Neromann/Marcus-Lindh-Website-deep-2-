# Marcus Vale — Magician Website

Next.js 14 project. Ready to deploy to Vercel.

## Local dev

```bash
npm install
npm run dev
```

Then open http://localhost:3000

## Deploy to Vercel (3 steps)

1. Push this folder to a GitHub repo
2. Go to vercel.com → New Project → import the repo
3. Click Deploy — done. Vercel auto-detects Next.js, no config needed.

## Customisation

- **Name/copy** — find/replace `Marcus Vale` throughout the components
- **Images** — replace Unsplash URLs with real photos in each component
- **Video IDs** — swap `dQw4w9WgXcQ` in `Clips.jsx` with real YouTube video IDs
- **Email** — wire up the contact form in `Contact.jsx` using Resend, Formspree, or EmailJS
- **Creations** — edit the `creations` array in `Creations.jsx`
- **Shows** — edit the `upcomingShows` array in `Shows.jsx`

## Structure

```
src/
  app/
    layout.jsx      ← fonts + metadata
    page.jsx        ← assembles all sections
    globals.css     ← design tokens + shared styles
  components/
    Navbar.jsx / .module.css
    Hero.jsx / .module.css
    Shows.jsx / .module.css
    About.jsx / .module.css
    Events.jsx / .module.css
    Clips.jsx / .module.css
    Creations.jsx / .module.css
    Contact.jsx / .module.css
    Footer.jsx / .module.css
```
