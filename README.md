📄🤖 AI-Powered Resume Generator using Google Gemini + n8n
🚀 Multi-Job Intake | 📑 ATS-Friendly LaTeX Resumes | 📬 Auto Email Delivery

Super excited to share a project I just completed that uses AI + automation to generate personalized, job-specific resumes from multiple job descriptions at once—and delivers them directly via email.

This workflow not only reduces manual work, but also enhances resume relevance and presentation with Gemini AI, LaTeX formatting, and modular n8n automation.

🔍 Project Overview

This system converts JSON-based job inputs into tailored, AI-generated resumes using a combination of:

✅ Google Gemini Pro (via AI Agent)
✅ n8n low-code automation
✅ LaTeX for formatting
✅ Gmail for delivery

Each resume is contextualized to its job and formatted for ATS compatibility.

🧩 How the Workflow Works

1. 📥 Webhook Input (Postman)
   The process begins with a simple POST request containing one or more job descriptions in JSON

2. 🔁 Smart Splitting + Looping
   The workflow breaks the input into separate job objects and loops over each, ensuring parallel and clean handling** of every role.

3. 🧠 AI Agent with Google Gemini Pro
   For each job entry:
   The AI receives personal resume details + job description
   It enhances the resume with job-aligned skills, responsibilities, and accomplishments
   Outputs structured content using Structured Output Parser
   Ensures clarity, ATS optimization, and logical flow

4. 📄 Resume as LaTeX Code
   The AI output is passed to a LaTeX formatting template which:

   * Builds a professional, elegant resume layout
   * Structures the content with clear sections for Summary, Experience, Skills, Certifications etc.
   * Produces clean, PDF-ready LaTeX output

5. 📧 Individual Resume Delivery
   Each resume is emailed separately to the recipient using the Gmail node in n8n.
   ✅ No merge confusion
   ✅ Clear job-to-resume mapping

 ✅ Features at a Glance

✔ Multiple job descriptions handled in a single run
✔ Role-specific AI resume tailoring with Google Gemini
✔ ATS-optimized LaTeX formatting
✔ Smart structured output parsing for cleaner results
✔ Auto-generated LaTeX code for resume documents
✔ Modular n8n implementation (visual-first, low-code)
✔ Individual email dispatch per job input

⚙ Tech Stack

* n8n – Visual automation logic
* Google Gemini Pro – LLM-powered resume generation
* Structured Output Parser – For clean data handling
* LaTeX – For pixel-perfect ATS-friendly resume formatting
* Gmail Node – To deliver each resume via email
* Postman – For testing and sending job input

💡 Why It Matters

In today's job market, customizing resumes for every role is critical—but time-consuming. This project demonstrates how AI + automation can:

🔹 Reduce time spent on tailoring resumes
🔹 Maintain high quality and relevance
🔹 Deliver ready-to-use outputs without manual formatting
🔹 Boost productivity for job seekers and professionals alike

🔗 #n8n #GoogleGemini #GeminiPro #ResumeAutomation #ATSFriendly #LaTeXResume #AIProjects #WorkflowAutomation #Postman #LLMApplications #AIResumeBuilder #GenerativeAI #JobTech #LowCodeAI #ProductivityTools #AutomationWithAI #NoCode #CareerTools #JobSearchAI
