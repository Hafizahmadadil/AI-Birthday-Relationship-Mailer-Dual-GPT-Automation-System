🎯 Overview

AI Birthday Relationship Mailer is an advanced n8n automation that sends personalized birthday wishes using dual GPT models — one for family & friends and another for customers/students with promotional offers.
It intelligently reads data from Google Sheets, checks for birthdays, fetches offers from Google Docs, and delivers customized HTML emails through Gmail automatically at midnight.

⚙️ How It Works

Cron Node → Triggers daily at midnight (Asia/Karachi).

Google Sheets Node → Reads all contact details and birthday dates.

IF Node → Checks if today’s date matches any birthday.

Filter Node → Splits recipients into Customers or Friends/Family.

Google Docs Node → Retrieves course offer text dynamically.

GPT Nodes (2) →

Model 1: Emotional message generator (Friends & Family).

Model 2: Professional message + offer (Customers/Students).

Gmail Nodes → Sends personalized HTML emails using elegant blue-gold templates.

💡 Key Features

Dual GPT message generation (tone-based personalization).

Dynamic offer integration via Google Docs.

Automatic daily trigger — fully hands-free operation.

HTML-based professional email design.

Easily customizable for WhatsApp, SMS, or CRM extensions.

🧰 Tech Stack

n8n (workflow automation)

OpenAI GPT-3.5

Google Sheets API

Google Docs API

Gmail API

🚀 Future Improvements

Add WhatsApp & SMS integration via Twilio.

AI-generated greeting images using DALL·E or Leonardo AI.

Add analytics dashboard for sent messages.

Deploy as a SaaS micro-service for small businesses.

📺 Demo Video

Watch the full video from attached file

👨‍💻 About the Creator

I’m Hafiz Ahmad Adil, an AI Automation Trainer & AI/ML Engineer passionate about building real-world automations using n8n, GPT, and AI APIs.
I create beginner-friendly tutorials, automation projects, and AI workflows for learners in Pakistan and beyond.
