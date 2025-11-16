# 🚀 TaskMinder – AI Meeting Workflow Agent

Turn raw meeting recordings into tasks, decisions, and project updates automatically.

🎯 Overview

MeetingNode is a smart AI-powered tool that helps teams avoid losing important meeting decisions.
You just log in → upload your meeting video → get auto-generated insights.

This project includes:

🎨 A creative animated Login Page

📤 A beautiful Upload Page to submit meeting recordings

🎧 Video → Transcription → Task Extraction (via backend / n8n)

🔗 Easy integration with project management tools like Notion / Jira / Slack

✨ Features
🔐 Elegant Login Page

Smooth animations

Modern UI styling

Ready for future authentication integration

📥 Upload Meeting Page

Collects all required meeting metadata:

Meeting Title

Meeting Date

Day of the Week

Number of Attendees

Attendee Names

Video Upload (.mp4, .mov, etc.)

“Upload & Process” button to trigger backend workflow

⚙️ Workflow Automation

(Backend handled via n8n or custom API)

Auto-transcribe meeting

Extract tasks, decisions, owners

Push to Notion / Slack / Jira

Store meeting summaries

🛠 Tech Stack

HTML5

CSS3 (custom animations + gradients)

JavaScript (Vanilla)

Visme Animations for UI motion

n8n for backend automation

Netlify / Vercel / GitHub Pages for deployment

📂 Project Structure
/
├── index.html          # Login + Upload page (SPA content switching)
├── assets/             # images, animations, icons (optional)
├── css/                # stylesheets (if separated)
├── js/                 # scripts (if separated)
└── README.md           # you are here
