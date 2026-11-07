# Tejumola & Victor — Wedding Invitation

A single-page, mobile-first digital wedding invitation: wax-sealed envelope that opens with light, arched chapel hero, scratch-to-reveal date, illustrated timeline, live countdown, venues with map links, and an RSVP (with plus-one option) that sends the reply over WhatsApp.

No build step, no dependencies: everything is in `index.html`.

## Edit the details
Open `index.html` and edit the `CONFIG` block at the top of the `<script>`:
names, parents, date/time (`dateISO`), venues, map searches, timeline, RSVP deadline,
and `rsvpWhatsApp` (the number that receives RSVPs — country code first, digits only).

## Deploy on Vercel
1. Import this repository at https://vercel.com/new
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. Every push to `main` redeploys automatically.

After the first deploy, change the `og:image` meta tag to the full URL
(e.g. `https://your-site.vercel.app/og.png`) so WhatsApp shows the preview image.

## Preview locally
Open `index.html` in a browser, or run `npx serve .`
