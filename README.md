
# Tesfay Brhanu — Attorney Website (React + Tailwind)

## What this is
A modern React + Tailwind website with an appointment booking form.  
The booking form posts to Formspree (replace the endpoint in `src/App.jsx`) so you receive booking requests by email.

## Quick local run
1. Install Node 18+.
2. Run `npm install`
3. Run `npm run dev` to start the local dev server.

## Deploy options (Netlify or Vercel)
### Netlify (recommended)
1. Create a repository on GitHub and push this project.
2. On Netlify, click **New site > Import from Git** and connect the repo.
3. Build command: `npm run build`  
   Publish directory: `dist`
4. Set environment variables if needed. For Formspree, no env required.
5. Optionally, enable Netlify Forms or add serverless functions.

### Vercel
1. Import project from GitHub.
2. Vercel detects Vite. Use default settings.
3. Deploy.

## Booking automation (optional)
- To automatically add confirmed bookings to Google Calendar:
  1. Create a Formspree account and connect your email.
  2. Use Zapier: trigger = Formspree new submission; action = Google Calendar create event.
  3. Alternatively, use Calendly and embed the Calendly scheduling widget (recommended for full automation).

## How to customize
- Replace contact info in `src/App.jsx`.
- Replace Formspree endpoint with your own: https://formspree.io
- To use Calendly, replace the booking form section with Calendly embed code.

