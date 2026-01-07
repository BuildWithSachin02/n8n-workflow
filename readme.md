# n8n Automation Workflows Repository
--
This repository contains automation workflows built using **n8n**, a powerful open-source workflow automation tool.

The purpose of this repository is to demonstrate how real-world business processes can be automated without traditional backend code, using APIs, triggers, and integrations.

----

## 🚀 What is n8n?

**n8n** (pronounced as *n-eight-n*) is a **workflow automation platform** that allows you to connect different services and automate tasks using a visual, node-based interface.

Instead of writing backend code, workflows are created using:
- Triggers
- Actions
- API integrations
- OAuth authentication
- Conditional logic

---

## 📂 What This Repository Contains

This repository includes:

- Multiple **n8n workflows**
- Real-world automation use cases
- Google APIs integration
- OAuth 2.0 authentication
- Form handling automation
- Email automation
- Data storage using Google Sheets

> ⚠️ **Note:**  
> n8n workflows are stored inside the n8n application and database.  
> That is why you will not see traditional `.js` or `.html` files here.

---

## 🧠 Why There Is No Traditional Code

Unlike normal web projects:

- ❌ No frontend code
- ❌ No backend server code
- ❌ No database schema files

Instead:
- All logic exists inside **n8n workflows**
- Nodes replace backend functions
- API calls replace server logic

Workflows can be **exported as JSON** if required.

---

## 🔗 Example Workflow Structure

Trigger Node
↓
Data Processing Node
↓
External API (Google / Gmail / Sheets)
↓
Final Action (Store / Send / Update)

yaml
Copy code

---

## 🧩 Types of Workflows Created

### ✔ Form Automation
- Captures form submissions
- Processes user input
- Sends automated responses

### ✔ Google Sheets Automation
- Appends rows automatically
- Updates existing records
- Uses OAuth 2.0 authentication

### ✔ Email Automation
- Sends emails using Gmail
- Dynamic subject & message
- Uses form data in emails

### ✔ API-Based Automation
- Uses Google APIs
- Handles permissions & scopes
- Secure OAuth credentials

---

## 🔐 Authentication & Security

This project uses **OAuth 2.0** authentication.

Enabled APIs:
- Google Sheets API
- Google Drive API
- Gmail API

OAuth configuration includes:
- Redirect URLs
- Test users
- Client ID & Client Secret
- Consent screen setup

---

## 🛠 Tools & Technologies Used

- **n8n**
- Google Cloud Console
- OAuth 2.0
- Google Sheets API
- Google Drive API
- Gmail API
- REST APIs
- JSON-based workflows

---

## 💡 Skills Demonstrated

- Workflow automation logic
- OAuth authentication handling
- API integration
- Data mapping & transformation
- Error handling in workflows
- Real-world automation design
- No-code / Low-code development

---

## 📌 Use Cases

This type of automation can be used for:
- Contact form handling
- Lead management
- CRM automation
- Email notifications
- Data logging
- Business process automation

---

## 📤 Deployment

Workflows are currently tested in **local n8n environment**.

They can be deployed to:
- VPS
- Docker
- Cloud servers
- n8n Cloud

---

## 📎 Author

**Sachin Yadav**  
Full-Stack Developer | Automation Enthusiast  

GitHub: https://github.com/BuildWithSachin02

---

## 📄 License

This project is created for learning, demonstration, and portfolio purposes.
