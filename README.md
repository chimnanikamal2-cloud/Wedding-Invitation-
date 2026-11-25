# Royal Wedding Invitation Website

A responsive, multi-page Indian wedding invitation starter website.

## Pages
- `index.html` — animated invitation cover, welcome and live countdown
- `story.html` — couple's story
- `events.html` — wedding functions and venue details
- `gallery.html` — sample photo gallery
- `rsvp.html` — RSVP form that sends the response to the family's WhatsApp

## Personalise before publishing
1. Open all HTML files and replace placeholders such as `[GROOM NAME]`, `[BRIDE NAME]`, `[WEDDING DATE]`, `[VENUE NAME]`, `[CITY]`, and family names.
2. In `script.js`, set `WEDDING_DATE` in local time using `YYYY-MM-DDTHH:MM:SS`.
3. Set `FAMILY_WHATSAPP` to the family's full WhatsApp number with country code, digits only (India: `91` + 10-digit number).
4. Add your own photographs. In `gallery.html`, replace sample image URLs with your image file paths or hosted image URLs. Replace the story placeholder with a couple photograph if desired.
5. For music, add a legally usable MP3 file (for example `assets/wedding-music.mp3`) and set `MUSIC_FILE` to that path in `script.js`. Browsers require a user tap before audio can play.
6. Update the Google Maps link in `events.html` with the exact venue address.

## Free hosting
### GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a new public repository, e.g. `wedding-invitation`.
3. Upload all website files and folders from this package to the repository root.
4. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. GitHub will provide a public website URL after deployment. Share that URL or create a QR code for it.

You can also deploy the folder with Netlify Drop. Do not put private phone numbers or sensitive family details in a public repository unless you are comfortable making them public.

## Important notes
- This is a static front-end starter. The RSVP form opens WhatsApp with a pre-filled message; it does not store responses in a database.
- The opening animation appears on the first visit in a browser session.
- Replace the sample gallery images with photographs you have permission to share.
- Background music is intentionally not bundled. Add a track you own or are licensed to use.
