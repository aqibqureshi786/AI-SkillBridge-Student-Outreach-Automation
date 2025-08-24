AI SkillBridge – Student Outreach Automation

Automated email campaign workflow built with n8n to help AI SkillBridge reach students about our free AI bootcamps.
This workflow personalizes outreach, sends automatic follow-ups, and stops sending once a student replies.

✨ Features

📧 Send personalized bulk emails via Gmail

🔄 Automatic follow-up sequence (Day 0, Day 3, Day 7)

⏸ Stops follow-ups when student replies

📊 Manage students easily through Google Sheets

🗓 Flexible scheduling (hourly, daily, custom)

🚫 Option to skip weekends

🔑 Secure OAuth2 Gmail + Sheets integration

📂 How It Works

Google Sheets → Stores student data (name, email, placeholders).

Email Sequence → Predefined messages (Bootcamp invite, reminder, final chance).

Gmail Node → Sends emails with tracking ID for this campaign.

Reply Detection → Checks Gmail threads, stops if student has replied.

Scheduler → Runs automatically (default: every hour).

⚙️ Setup Instructions

Clone Google Sheet

Copy this template sheet
.

Update the Settings node in n8n with your sheet URL.

Configure Email Sequence

Edit the Email Sequence node to customize your messages.

Update {form_link} with your Google Form link.

Update {name} or any placeholders to match your sheet columns.

Connect Credentials

Add your Gmail and Google Sheets credentials in n8n.

Use the official AI SkillBridge account, not personal Gmail.

Adjust Schedule

Default: runs every hour.

Change to daily (e.g., 10 AM) if preferred.

Test with Dummy Data

Use 2–3 test emails before launching with real student data.

🚀 Use Case

Invite students to free AI SkillBridge bootcamps

Highlight free laptops for top 100 students

Share exciting career opportunities

Ensure no student misses the registration form

📌 Example Email (Day 0)

Subject: 🚀 Join Our Free AI Bootcamp + Chance to Win a Laptop!

Hi {name},
We’re thrilled to announce that AI SkillBridge is launching Free AI Bootcamps for students!

✨ What’s in it for you?

100% Free AI Training Bootcamps

Free Laptops for the Top 100 Students 💻

Amazing Opportunities: internships, projects & career growth 🌟

👉 Register here: Bootcamp Form

More info: AI SkillBridge Website

👨‍💻 Author

Created by Aqib @ AI SkillBridge
