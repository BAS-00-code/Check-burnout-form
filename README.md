# Check-burnout-form
Interactive 7-question burnout risk check. Captures name and email before showing a Green / Amber / Red result. Sends data to Make webhook → Mailerlite.
Stack
Single HTML file — Netlify hosting, Make automation, Mailerlite email.
Deploy
Drop index.html into a folder and drag onto Netlify dashboard.
Webhook
Find sendToMailerlite in the script and replace YOUR_MAKE_WEBHOOK_URL with your Make webhook URL.
