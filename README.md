NexusConf — Live Webinar Landing Page
A modern, responsive, single-file webinar registration landing page built with HTML5, Tailwind CSS, and vanilla JavaScript. Designed for zero-dependency static hosting on GitHub Pages.
✨ Features
Responsive Design: Fully adaptable layout optimized for mobile, tablet, and desktop screens.
Live Countdown Timer: Automatically calculates and counts down to the upcoming session date in real time.
Interactive Registration Form: Includes client-side validation and transitions smoothly into a personalized confirmation pass with a unique Pass ID.
One-Click Calendar Invite (.ics): Dynamically generates and downloads an .ics calendar file so attendees can add the event to Google Calendar, Apple Calendar, or Outlook.
Shareable Link: Built-in one-click link copy functionality for easy social sharing.
Complete Event Sections: Features a minute-by-minute session agenda, key takeaways, speaker spotlight cards, and an interactive FAQ accordion.
🛠️ Tech Stack
HTML5 — Semantic markup
Tailwind CSS (via CDN) — Utility-first styling without a build step
Font Awesome (via CDN) — Crisp vector icons
Vanilla JavaScript — Countdown logic, form validation, and .ics file generation
🚀 Deployment on GitHub Pages
1. Upload index.html and README.md to the root directory of your public GitHub repository.
2. Go to your repository's Settings > Pages.
3. Under Build and deployment, set Source to Deploy from a branch.
4. Select your branch (e.g., main) and the / (root) folder, then click Save.
5. Wait 1–2 minutes for GitHub to build your site, then visit your live URL at https://<your-username>.github.io/<repository-name>/.
🎨 Customization
Because the entire webpage lives inside a single index.html file, you can easily customize it directly in GitHub's web editor:
Event Title & Details: Edit the hero section text inside <section> near the top of index.html.
Countdown Target Date: Locate the targetDate variable inside the <script> tag at the bottom of index.html to set a fixed date and time.
Speakers & Agenda: Update the speaker names, bios, image URLs, and timeline items in the #agenda and #speakers sections.
📄 License
This project is open-source and free to use for personal or commercial events.
