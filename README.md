# Dr. Laha's Dental Clinic Website

A responsive React + Vite + TypeScript website for Dr. Laha's Dental Clinic in Dhansar, Dhanbad.

## Run locally
1. Install Node.js 20 or newer.
2. In this folder, run `npm install`.
3. Run `npm run dev`.
4. Open the local URL shown by Vite.

## Production build
Run `npm run build`. Upload the generated `dist/` directory to Netlify, or import this project into Vercel and use `npm run build` as the build command with `dist` as the output directory.

## Before publishing
- Confirm that `+91 62070 12979` is the clinic's WhatsApp-enabled number. Update `WHATSAPP` in `src/main.tsx` if needed.
- Add the clinic's real Google Business Profile reviews URL to `REVIEWS_URL` in `src/main.tsx`.
- Confirm current opening hours.
- Replace the illustrative stock dental photos with clinic-owned photos if available. Current images load from Unsplash and are not represented as photos of the actual clinic or staff.
- The appointment form opens WhatsApp with a prefilled request. It does not claim an appointment is confirmed.
- Review and approve all clinic details and service listings before publishing.

## Features
- Responsive navigation and mobile menu
- 18 services grouped with interactive category filters
- WhatsApp enquiries that include the selected service
- Appointment enquiry form validation with WhatsApp handoff
- Click-to-call, directions, mobile action bar, and floating WhatsApp shortcut
- SEO title, description, Open Graph metadata, and favicon
- Respects reduced-motion preferences
