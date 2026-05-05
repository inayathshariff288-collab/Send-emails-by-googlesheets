# 📧 AI Email Automation using n8n + Google Sheets

Send personalized emails automatically using Google Sheets + Gmail — no manual work required.

---

## 🚨 The Problem

Most businesses still send emails manually:

- Copy → paste → send  
- Follow-ups get missed  
- Errors happen  
- No tracking  

This wastes time and limits growth.

---

## 💡 The Solution

This workflow automates the entire process:

👉 Just update your Google Sheet  
👉 Emails get sent automatically  

No manual effort. No chaos.

---

## ⚡ What This Workflow Does

- 📊 Reads data from Google Sheets  
- 📅 Filters emails based on date  
- 📌 Sends only pending emails  
- 📧 Sends personalized emails via Gmail  
- 🔄 Updates status in Google Sheets  

---

## 🔄 How It Works

```
Google Sheets → Filter Status → Filter Date → Gmail → Update Sheet
```

### Step-by-step:

1. **Google Sheets Trigger**  
   Watches for new or updated rows  

2. **Filter Status**  
   Sends only emails marked "Waiting for sending"  

3. **Filter by Date**  
   Sends emails scheduled for today  

4. **Gmail Node**  
   Sends personalized email  

5. **Update Google Sheet**  
   Marks email as sent  

---

## 🎯 Use Cases

- Lead follow-ups  
- Customer onboarding  
- Appointment reminders  
- Bulk outreach campaigns  
- Marketing automation  

---

## 🔥 Benefits

- ⏱️ Saves hours of manual work  
- 🎯 Sends emails to the right person at the right time  
- 💬 Personalized communication  
- 📊 Real-time tracking in Google Sheets  
- 🔁 Consistent workflow  

---

## 🛠️ Setup Guide

### Requirements

- n8n (self-hosted or cloud)  
- Google Sheets account  
- Gmail account  

---

### Steps

1. Import the workflow JSON into n8n  
2. Connect your Google Sheets credentials  
3. Connect your Gmail account  
4. Update your Google Sheet with:
   - Name  
   - Email  
   - Status  
   - Send Date  
5. Run the workflow  

---

## 📥 Import Workflow

👉 Import the JSON file from this repository into n8n  

---

## 📊 Example Sheet Format

| Name | Email | Send Date | Status |
|------|------|----------|--------|
| John | john@email.com | 2026-05-10 | Waiting for sending |

---

## ⚙️ Customization

You can easily:

- Modify email templates  
- Add attachments  
- Integrate CRM tools  
- Connect Slack / Telegram notifications  
- Add AI personalization  

---

## 🚀 Pro Tip

Combine this workflow with AI tools to:

👉 Generate personalized email content automatically  

---

## 📬 Want This for Your Business?

If you want a customized automation system:

👉 Message me on LinkedIn

---

## ⭐ Support

If you found this useful:

- ⭐ Star this repo  
- 🔁 Share with others  
- 👤 Follow me for more AI automation systems  

---
