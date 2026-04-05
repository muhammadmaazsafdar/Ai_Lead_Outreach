# AI Lead Outreach Machine

> Automates personalized cold email outreach — drops a lead in a Google Sheet, AI writes the email, Gmail sends it, sheet updates itself.

![Workflow Screenshot](workflow.png)

---

## What It Does

Most businesses waste hours writing cold emails manually. This workflow eliminates that. Add a lead's name, company, role, and email to a Google Sheet — the rest happens automatically. Groq's AI writes a personalized email, Gmail sends it, and the sheet marks it as "Sent."

## Workflow

New Row in Google Sheets → Groq AI writes email → Gmail sends it → Sheet updates to "Sent"

## Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Groq API (Llama 3.1 8B) | AI email generation |
| Google Sheets | Lead input and status tracking |
| Gmail | Email delivery |

## Use Case

Built for small businesses and sales teams who want to automate cold outreach without writing a single email manually.

## Author

**Muhammad Maaz Safdar**
- GitHub: [@muhammadmaazsafdar](https://github.com/muhammadmaazsafdar)
- LinkedIn: [Muhammad Maaz Safdar](https://www.linkedin.com/in/muhammadmoaaz/)