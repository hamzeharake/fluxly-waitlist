# Fluxly Waitlist

Email capture system for fluxly.nl — collects early access signups and stores them automatically in Google Sheets.

🔴 **Live on:** [fluxly.nl](https://fluxly.nl)

## What it does

- Visitors enter their email on fluxly.nl
- Email is sent to n8n via webhook
- Automatically saved to Google Sheets with timestamp
- Coming soon page with brand styling

## Stack

- **n8n** — webhook + Google Sheets integration
- **Google Sheets** — email storage
- **HTML/CSS/JavaScript** — custom landing page

## Architecture

Visitor enters email
→ Form submit (fetch API)
→ n8n Webhook
→ Google Sheets (append row)
