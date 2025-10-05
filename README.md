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
<img width="1728" height="1083" alt="Screenshot 2025-10-05 at 8 17 53 PM" src="https://github.com/user-attachments/assets/34301cd1-475e-413f-b710-00e6dde604f8" />

<img width="1728" height="1083" alt="Screenshot 2025-10-05 at 8 18 43 PM" src="https://github.com/user-attachments/assets/32e41d32-e34a-4ee2-893a-7acf2f191e4d" />

<img width="1728" height="1117" alt="Screenshot 2025-10-05 at 8 17 30 PM" src="https://github.com/user-attachments/assets/1eb0c646-d024-4f38-982f-c26e0bab5f18" />
