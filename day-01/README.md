# Day 01 — Google Form → Thank You Email

**Challenge:** #30DaysOfAutomation  
**Tool:** Zapier  
**Difficulty:** ⭐ Beginner  
**Date:** March 25, 2025

---

## 🔧 What I Built

A two-step automation that sends an automatic thank-you email to anyone who submits a Google Form.

---

## ⚡ How It Works

```
[Google Form submission]
        ↓
   Zapier trigger
   (New Form Response)
        ↓
   Gmail action
   (Send Email to respondent)
```

**Step 1 — Trigger:** Zapier listens for a new response on a specified Google Form.  
**Step 2 — Action:** Gmail automatically sends a personalised thank you email to the respondent's email address.

---

## 💡 Why This Matters

This is the foundation of almost every client-facing automation:
- Event registrations
- Waitlist signups
- Contact forms
- Job applications

Master this pattern and you can automate the first touchpoint of any business process.

---

## 🛠️ Tools Used

- [Zapier](https://zapier.com) — automation platform
- Google Forms — form trigger
- Gmail — email delivery

---


## 🔁 How to Replicate

1. Create a Google Form with an email field
2. In Zapier, create a new Zap
3. Set trigger → **Google Forms: New Response in Spreadsheet**
4. Set action → **Gmail: Send Email**
5. Map the email field from the form to the "To" field in Gmail
6. Customise your thank you message
7. Test and publish

---

## 🧠 What I Learned

- How Zapier triggers work with Google Workspace
- How to map dynamic fields (respondent's email, name) into email templates
- The basic trigger → action pattern that powers all no-code automation

---

*← Back to [main challenge](../README.md)*
