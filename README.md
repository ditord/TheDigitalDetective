This README.md is designed to be professional yet inviting for an educational project. It uses a "cyberpunk/hacker" aesthetic to get young participants excited about the mission.

🕵️‍♂️ Project: Operation Digital Detective
An Interactive OSINT CTF for Emerging Investigators
Welcome to Operation Digital Detective, a beginner-friendly Capture The Flag (CTF) game designed to teach Open Source Intelligence (OSINT), digital literacy, and verification skills to young people.

This repository contains the frontend "Terminal" interface and the blueprint for the backend "Engine" using Google Forms.

🎮 Game Overview
Teams of 5 act as a remote intelligence unit. They must navigate through a series of increasingly difficult challenges—ranging from geolocating a single photo to uncovering hidden metadata in public documents.

🧩 The Challenges
Geolocation: Identify exact coordinates using visual clues and satellite imagery.

Social Engineering Analysis: Scrutinize fake profiles to find hidden links.

Metadata Forensic: Extract "hidden" data from images and PDFs (EXIF data).

Chronolocation: Determine the time of day an event occurred using sun and shadow positions.

🛠 Tech Stack
To keep this project lightweight and easy to deploy for a workshop, we use:

Frontend: Static HTML5 / CSS3 (The "Hacker Terminal" UI).

Engine: Google Forms with Response Validation (The "Gatekeeper").

Scoreboard: Google Sheets (Linked to the Form for real-time tracking).

🚀 Quick Start (Deployment)
1. Setup the Google Form
Create a new Google Form.

Enable Settings > Make this a quiz.

Create a section for each puzzle.

For each answer, use Response Validation (set to "Text" > "Contains") to ensure players can only proceed with the correct answer.

2. Deploy the Frontend
Fork this repository.

Open index.html and replace YOUR_GOOGLE_FORM_LINK with your actual form link.

Go to GitHub Settings > Pages and set the branch to main.

Your game is now live at https://[your-username].github.io/[repo-name].

👥 Suggested Team Roles
To ensure everyone in a team of 5 is engaged, we recommend these roles:

Lead Investigator: Coordinates the team and manages the Google Form.

Map Specialist: Expert in Google Street View and satellite imagery.

The Archivist: Focuses on historical data and Wayback Machine searches.

Forensic Tech: Handles image analysis and metadata tools.

Fact Checker: Verifies all leads before they are submitted.

📜 Rules of Engagement
No Active Interaction: Do not contact, message, or interact with any accounts found during the game.

Stay Within Scope: Only use public search engines, maps, and tools. No hacking or "brute-forcing" is required.

Collaborate: The best investigators share clues.

🛠 Tools Recommended for Players
Google Lens / Reverse Image Search

SunCalc (for shadows/time)

Wayback Machine (for deleted info)

Aperi'Solve (for image forensics)