# Izzoh Mental Wellness & Community Advocacy — Website

## Files
- `izzoh_complete_website.html` — complete standalone website.
- This HTML contains the website styling, navigation, JavaScript interactions, social links, appointment form, Gallery, News Updates and the embedded advocate portrait.

## How to use
1. Save `izzoh_complete_website.html` to your computer or phone.
2. Open it in any modern web browser.
3. No web server, database or build process is required for the current version.
4. The navigation tabs are executable JavaScript tabs and work directly from the HTML file.

## Main sections
- Services
- Mental Wellness
- Advocacy
- Our Approach
- About the Advocate
- Appointments
- Media
- Gallery
- News Updates
- Contact

## About the Advocate
The former **Bio** tab has been renamed **About the Advocate**. The section includes the advocate portrait and merges the profile information with the professional approach, values and mission information that was previously presented separately.

The current source website does **not contain specific academic qualifications, degree names, institutions, graduation dates or professional certificates**. Those details have therefore not been invented or added.

## Gallery
The Gallery currently uses visual placeholders representing:
- Community Engagement
- Mental Wellness Awareness
- Training & Awareness
- Advocacy Campaigns
- Wellbeing Activities
- Community Support

Replace these placeholders with actual photographs when available.

## News Updates
The News Updates section is structured for:
- Mental wellness awareness updates
- Community advocacy activities
- Announcements
- Appointment and engagement notices

The current entries are general placeholder/update content and can be replaced with dated news stories.

## Appointments
The appointment form prepares an email request using the visitor's:
- Name
- Phone number
- Email
- Selected service
- Preferred date
- Message

The form opens the visitor's email client using a `mailto:` action; it does not require a backend server.

## Social/contact links
The website includes the contact and social-media addresses already supplied for the site. Verify these links before public deployment if any account handles or contact details have changed.

## Editing tips
- Search for `<section class="panel" id="bio">` to edit About the Advocate.
- Search for `<section class="panel" id="gallery">` to edit Gallery content.
- Search for `<section class="panel" id="news">` to edit News Updates.
- Search for `sendAppointment` to modify appointment-email behavior.
- The advocate portrait is embedded as Base64 inside the HTML, so the page remains self-contained.

## Deployment
The file can be uploaded directly to ordinary static hosting such as a web-hosting file manager, GitHub Pages, Netlify, Vercel static hosting, or another service that serves HTML files.

## Important content note
The website should only publish professional titles, qualifications, credentials and claims that are accurate and verifiable. Add academic/professional credentials only after supplying the exact information you want published.
