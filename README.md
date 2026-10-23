# Ezen Baitul Aman Cultural Center — Website Starter

A responsive, multilingual (Bangla, English, Arabic, Korean) static website starter for Ezen Baitul Aman Cultural Center.

## Included
- Responsive desktop and mobile layout
- Language switcher with Arabic right-to-left layout
- Mosque, Islamic school, Quranic Arabic course, adult Qur'an learning, events, news, contact and gallery sections
- Custom SVG brand mark and favicon
- Google Maps name-search link (replace with the verified exact location)
- No build tools required

## Important before publishing
1. Confirm the full mosque address and replace the location placeholder.
2. Replace the Google Maps search link with the mosque's exact verified Google Maps share link.
3. Add an official email address and any public contact/social links.
4. Replace sample news cards with real announcements and dates.
5. Check all four language translations, particularly official names and event details.
6. Obtain permission before publishing photos of children or community members.
7. Test the site on a phone and computer.

## How to preview
Open `index.html` in a browser. For local testing, you can also run a simple static server from this folder:
`python -m http.server 8000`
Then open `http://localhost:8000`.

## Free publishing with Netlify
1. Create a Netlify account.
2. Unzip the package.
3. Drag the whole `ezen-baitul-aman-cultural-center` folder into Netlify Drop (or follow Netlify's current manual deploy flow).
4. Netlify will provide a temporary public URL.
5. Test the public URL on phone and desktop.

## Content editing limitation
This starter is a static website. The language selector works, but the sample news/events are currently edited in `index.html`; there is no secure admin panel, database, login, registration backend, or payment processing yet. Do not publish sensitive personal information in static files.

## Recommended next upgrade
Connect a CMS with authenticated editing and image uploads (for example, Decap CMS with a suitable Git-based deployment and identity/authentication setup) or choose a managed website platform. Configure access securely before enabling public editing. A CMS setup needs hosting/provider configuration and cannot be enabled merely by adding a front-end login screen.


## Address details supplied by the user
- Address: 92-38 Yuhyeonsaksi-ro, Yangchon-eup, Gimpo-si, Gyeonggi-do, Gimpo, South Korea 10047
- Email: ezenbaitulaman2020@gmail.com
- Phone / WhatsApp: +82 10-5944-9654
- Messenger page name: Ezen Baitul Aman Masjid - ইজেন বাইতুল আমান মসজিদ

The Google Maps button searches using the supplied address; verify the exact pin before launch.


## Updated design draft (October 2026)
- Header branding updated to **Ezen Baitul Aman Mosque**.
- Added the selected circular cyan/white mosque logo asset (`assets/mosque-logo.png`).
- Updated the existing stylesheet toward sky blue, deep blue, white and gold while preserving the page structure and mobile layout.
- Language menu retains the four currently translated languages (Bengali, English, Arabic, Korean). Additional languages are listed as disabled “Coming soon” options so visitors are not misled into selecting untranslated content.
- Before publishing, review the logo crop, check all sections on mobile, and complete translations in stages. This ZIP does not deploy itself to Netlify.
