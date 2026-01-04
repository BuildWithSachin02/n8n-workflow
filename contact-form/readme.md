
# n8n Contact Form Automation

This project contains an **n8n automation workflow** that handles contact form submissions and automates data storage and email notifications.

## 🔧 What this workflow does

When a user submits a contact form:

1. The form data is captured using **n8n Form Trigger**
2. The data is stored in **Google Sheets**
3. A confirmation or notification email is sent using **Gmail**

This workflow is built and tested on **local n8n (localhost)** using OAuth authentication.

---

## 🧩 Workflow Structure

- **Trigger Node**
  - On Form Submission

- **Google Sheets Node**
  - Append row in a Google Sheet
  - Stores:
    - Name
    - Email
    - Phone
    - Submission Date
    - Form Mode

- **Gmail Node**
  - Sends an email using Gmail OAuth
  - Email is sent to the submitted email address

---

## 📂 Project Files

| File | Description |
|----|------------|
| `workflow.json` | Exported n8n workflow |
| `README.md` | Project documentation |

---

## 🚀 How to Use This Workflow

1. Install and run **n8n**
2. Open n8n editor
3. Click **Import workflow**
4. Upload `workflow.json`
5. Configure credentials:
   - Google Sheets OAuth
   - Gmail OAuth
6. Connect your Google Sheet
7. Activate the workflow

---

## 🔐 Authentication Used

- Google Sheets API (OAuth 2.0)
- Gmail API (OAuth 2.0)

> Note: The OAuth app is in **Testing mode**, so only added test users can authorize access.

---

## 🧪 Tested Environment

- n8n (Localhost)
- Google Sheets
- Gmail
- OAuth 2.0
- Windows OS

---

## 💡 Use Case

This automation is useful for:
- Portfolio contact forms
- Lead collection
- Small business websites
- Automated email responses

---

## 🧠 Author

Built by **Sachin Yadav**  
Web Developer | Automation with n8n

---
--output--

output:-    https://drive.google.com/file/d/1svyt1_ilZZ53cD6SyjW76JcvPwW8pR2D/view?usp=sharing

## 📌 Notes

- This repository contains **no frontend code**
- All logic is handled via **n8n workflow**
- Credentials are **not included** for security reasons
