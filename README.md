# Auto-Ai-Internship-Apllier
This project automatically generates and sends personalized internship application emails based on data stored in Google Sheets.
 
 #Demo Video watch Here-> 

🚀 Personal AI Internship Applier
    � � � � �
   An AI-powered automated internship application system that generates and sends personalized internship emails using workflow automation and LLM integration.


📖 Overview
  1.Personal AI Internship Applier is a scalable automation workflow designed to eliminate repetitive manual effort in internship applications.
  2.The system automatically Reads applicant data from Google Sheets
  4.Generates professional email content using AI
  5.Sends structured, ready-to-use emails via Gmail
  6.This project demonstrates real-world integration of AI with workflow orchestration and API-based automation.

 
 🏗️ System Architecture
   Google Sheets Trigger
          ↓
    AI Email Generation (Gemini)
          ↓
    Structured Output Parsing
          ↓
     Gmail API Dispatch
 
 
🛠️ Tech Stack
   *Category: Technology
   *Workflow Engine: n8n
   *AI Model: Google Gemini
   *Data Source: Google Sheets API
   *Email Service: Gmail API
   *Configuration: JSON Workflow


✨ Features
    ✔ AI-generated professional internship emails
    ✔ Fully automated workflow
    ✔ Structured JSON output handling
    ✔ Event-driven execution
    ✔ Scalable and modular design
    ✔ Clean separation of trigger, processing, and delivery layers


🚀 Installation & Setup
    1️⃣ Import Workflow: Install n8n (self-hosted or cloud) Import the provided JSON workflow file
    2️⃣ Configure Credentials: Google Sheets OAuth2,Google Gemini API Key,Gmail OAuth2
    3️⃣ Prepare Google Sheet Columns
        *Ensure the following fields exist:
            1.Full Name
            2.Email
            3.Position Applied
            4.Details
            5.Experience (Years)
            6.Skills


4️⃣ Activate Workflow
     Enable workflow execution to start automation.


🔐 Security & Best Practices
      *OAuth2 authentication used for all Google services
      *No credentials stored directly in repository
      *Recommended use of environment variables for API keys
      *Controlled email dispatch to prevent spam


📈 Use Cases
    *Engineering students applying for internships
    *Bulk internship outreach campaigns
    *AI-powered automation portfolios
    *Workflow automation demonstrations


    
