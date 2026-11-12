# Small-Office IT Support & Troubleshooting Portfolio Prompt

Welcome to the **Small-Office IT Support Prompt** repository. This project contains a comprehensive, highly-structured AI prompt designed to generate a complete suite of IT support artifacts for a small business environment. 

By utilizing the core prompt found in this repository, users can command Large Language Models (LLMs) to act as a Senior IT Support Lead and Technical Writer, producing automated diagnostic scripts, professional documentation, and clear office communications.

## 📄 Core Prompt File

The main engine of this project is the prompt file itself. Please refer to the following file to view, copy, and use the prompt:
**`01_IT_Support_Troubleshooting_Portfolio_Prompt.md`**

## 🎯 Purpose and Scope

Small businesses often lack a dedicated enterprise IT department. When technical issues arise, the responsibility often falls on an "IT-Officer-in-Charge" who may have minimal technical background. 

This prompt is engineered to bridge that gap by generating:
1.  **Automated Diagnostics:** PowerShell or Shell scripts that safely collect symptoms, check configurations, and document findings without risking system integrity.
2.  **Standardized Documentation:** Easy-to-follow runbooks and ticketing templates to establish a professional IT workflow.
3.  **Manager-Friendly Reporting:** Clear, jargon-free memos and incident reports suitable for non-technical stakeholders.

## ⚙️ How It Works

The prompt is divided into five strategic phases to ensure the AI generates high-quality, contextual outputs:

### 1. Scenario and Boundaries
You define the specific environment (number of users, shared devices, network policies). The prompt instructs the AI to operate within a "modest budget" and establishes strict rules for the diagnostic scripts it generates.

### 2. Narrowed-Down Diagnostics
Provides a framework for inputting specific user complaints (e.g., "The network printer isn't working"), assessing urgency, and triaging the impact.

### 3. Comprehensive Deliverables
When executed, the prompt forces the AI to generate a consistent portfolio of files, including:
*   `README.md` (Project overview)
*   `01_Service_Ticket_Template.md`
*   `02_Troubleshooting_Runbooks.md`
*   `03_Completed_Tickets_Template.md`
*   `04_Incident_Summary_Report.docx` (or Markdown)
*   `05_Office_Memo.docx` (or Markdown)
*   `06_Preventive_Maintenance_Checklist.md`

### 4. Communication Standards
The prompt is uniquely tailored to a realistic business context (specifically localized for a Philippine small-business workplace, utilizing `DD MMM YYYY` dates, 24-hour time, and clear separation of observed facts vs. assumptions).

### 5. Strict Quality Checks
Built-in guardrails ensure the AI provides safe stopping points, escalation criteria, redacts sensitive data (passwords/API keys), and keeps instructions accessible for beginner IT personnel.

## 🚀 How to Use

1. Open **`01_IT_Support_Troubleshooting_Portfolio_Prompt.md`**.
2. Copy the entire contents of the file.
3. Paste it into your preferred LLM (e.g., Gemini, ChatGPT, Claude).
4. Fill in the blank fields under **"1. Scenario and boundaries"** and **"2. Narrowed-down diagnostics"** with your specific simulated or real-world IT scenario.
5. Hit generate and watch the AI build a complete, professional IT support portfolio.

## 🤝 Contributing

Contributions to improve the prompt's safety guardrails, expand the deliverable templates, or adapt the communication standards for other locales are highly encouraged. Feel free to submit a Pull Request!