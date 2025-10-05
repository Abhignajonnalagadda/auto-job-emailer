# 🤖 Auto Job Emailer using n8n + OpenAI

Automate your job search by analyzing job descriptions and generating personalized cold emails using **n8n** workflows and **OpenAI GPT** — no manual typing, no context switching.

---

## 📘 Overview

This project automates the process of creating **personalized cold emails for job applications**.

Whenever you come across a job description (JD) — on LinkedIn, Naukri, or elsewhere — simply send it to your n8n webhook.  
The workflow automatically:

1. Analyzes the job description using GPT.  
2. Extracts key details like job title, company name, HR email, and required skills.  
3. Generates a short, polite, and personalized cold email to send to the HR.  

🚫 *Note:* This version does **not attach resumes** — purely text-based email generation.

---
## 🧠 How It Works

### Webhook Node
Receives the job description text as a JSON payload.

### GPT Node (HTTP Request or OpenAI)
Processes the text, extracts job details, and generates a personalized cold email.

### Response Node
Returns the GPT output in a clean JSON structure (or optionally sends it through Gmail).

## Preview
<img width="1728" height="972" alt="Screenshot 2025-10-05 at 9 10 25 PM" src="https://github.com/user-attachments/assets/00309c19-1dda-4140-8d59-4c8e251a2d3a" />
<img width="1728" height="1043" alt="Screenshot 2025-10-05 at 9 07 34 PM" src="https://github.com/user-attachments/assets/6b4ca227-81bb-486a-ae7b-dbdd74c7b3e2" />
<img width="1408" height="874" alt="Screenshot 2025-10-05 at 9 09 04 PM" src="https://github.com/user-attachments/assets/9a3c0411-1a4c-4516-9ab5-955570611c26" />
