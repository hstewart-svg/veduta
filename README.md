Veduta

CAE Executive Workspace

A personal command center for Chief Audit Executives — onboarding tracker, key contacts, 1:1 meetings, recruiting pipeline, audit plan, and AC meeting prep. Built to sync across laptop and iPhone.

Setup (One Time)

Step 1: Supabase Database

Go to your Supabase dashboard: https://supabase.com/dashboard
Select your Veduta project
Click SQL Editor in the left nav
Click New Query
Paste the entire contents of setup.sql
Click Run
That's it — all 7 tables are created with Row Level Security enabled.

Step 2: Deploy to GitHub Pages

Create a new GitHub repository called veduta
Upload index.html to the repo
Go to Settings → Pages
Set source to main branch / root
Your app will be live at https://yourusername.github.io/veduta
Step 3: First Sign In

Open the app
Enter your email and a password
First sign-in creates your account automatically
Use the same credentials on any device to sync data
Modules

Module	Description
Dashboard	Overview, stats, weekly reminders
Onboarding Tracker	6 tracks, 50+ pre-loaded items, status cycling
Key Contacts	Execs, external stakeholders, relationship tracking
1:1 Meetings	Per-person meeting log, action items, cadence
Recruiting Pipeline	Candidates by stage, source, last contact
Audit Plan	High-level coverage tracker by domain
AC Meeting Prep	Agenda, materials status, open items per meeting
Weekly Reminders (Dashboard)

Check Engage site
Check Workvivo
Review Teams channels
Send thought leadership article to a contact
Data & Security

All data stored in your personal Supabase instance
Row Level Security enabled — your data is private
Syncs across all devices via Supabase
No third-party analytics or tracking
Built by Heather Stewart · CAE · April 2026
