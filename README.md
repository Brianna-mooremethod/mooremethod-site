# The Moore Method — Website

One-page site for The Moore Method, Model Etiquette & Runway Academy (Atlanta).
Plain HTML, CSS and JavaScript in a single `index.html`. No build step, no installs.

## Before you launch: fill in your links

Open `index.html`, find the `CONFIG` block near the bottom, and fill in:

```js
const CONFIG = {
  bookingUrl: "",   // Stripe Payment Link (or Square / Calendly booking link) for the $50 deposit
  instagram: "",    // your handle without @, e.g. "themooremethod"
  contact: ""       // business phone or email students send their enrollment to
};
```

- When `bookingUrl` is set, a **Pay deposit** button appears after a student submits the form.
- When `instagram` is set, an **Open Instagram** button appears and your handle shows in the footer.

## Preview it on your computer

Double-click `index.html` to open it in your browser.

## Deploy to Vercel

1. Create a GitHub repository (e.g. `moore-method-site`) and upload `index.html` and this README.
2. In Vercel: **Add New → Project → Import** your repo. Framework preset: **Other**. No build command, no output directory needed.
3. Click **Deploy**. You'll get a `*.vercel.app` link.
4. Vercel's free Hobby plan is for non-commercial use only. A paid class business needs the **Pro** plan.
5. To use your own domain: **Project → Settings → Domains**, add `themooremethod.com` (or yours), and follow the DNS steps Vercel shows.

## Editing later

Every change you push to GitHub redeploys automatically. In Claude Code, open this folder and ask for changes, for example "add a testimonials section" or "change the Series price to $199."

## What's on the page

- Hero with tagline: *Poise. Presence. Professionalism.*
- Coach bio (Bri Moore)
- Six-part curriculum
- Pricing: Intro Workshop $45, Runway Ready Series $175, Private Session $85, Show Ready Package $225, Signature Intensive $375, plus add-ons
- Enrollment form that builds a copy-ready message, with an optional deposit link

Brand colors: Runway Black `#111111`, Pearl Ivory `#F7F3EC`, Champagne `#C9A66B`, Bronze `#7E5F32`.
Fonts: Bodoni Moda (headlines), Jost (body), loaded from Google Fonts.
