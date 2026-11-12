**Small-Office IT Support: Troubleshooting, Documentation, and Office Reporting AI Prompt**  
  
---  
**Copy-and-use prompt**  
  
---  
   
Act as a senior IT support lead and patient technical writer. Provide an a.) automated Powershell batch file or shell script solution, alongside the b.) needed documentation to troubleshoot the given scenario with its requirements; and c.) Notification memo / letter to the user and the office(s) affected when user support is being performed:  
**1. Scenario and boundaries**  
- Number of Windows desktop users:  
- Number, type and model of shared device(s):  
- Number, type and model of network devices:  
- General Firewall Policy for network devices:  
- Name(s) and description of shared folder(s):  
Assume a modest budget and no dedicated enterprise IT department.  
The generated script must have the ability to:  
- collect symptoms and ask useful diagnostic questions;  
- troubleshoot common, low-risk Windows and small-office issues;  
- distinguish user error, device problems, network problems, and  
 service/configuration problems;  
- document findings, actions, verification, and unresolved risks; in a text file in the Documents folder  
- write clear office memos and short incident/service reports for non-technical managers; in a text file in the Documents folder, including: a.) Diagnostic sequence: safe checks in a sensible order, withexpected observations, b) Likely cause: clearly label this as a hypothesis until verified. And c.) Resolution or escalation.  
- The script must remind the user/administrator the location of documentations, and that the user/administrator must paste it in the prescribed reporting format by the company.  
   
**2. Narrowed-down diagnostics and User Ticket**  
**User report:**   
**Type of support requested by User:**   
**Impact, urgency, and affected users (Triage):**  
   
**3. Deliverables**  
Generate the following as polished, consistent artifacts:  
- `README.md` --- overview, environment, scope, tools, and limitations.  
- `01_Service_Ticket_Template.md`  
- `02_Troubleshooting_Runbooks.md` --- concise runbooks for the reported case(s).  
- `03_Completed_Tickets_Template.md` --- sample template for completed work tickets.  
- `04_Incident_Summary_Report.docx` or Markdown equivalent --- manager-friendly report summarizing trends, impact, resolutions, and open issues.  
- `05_Office_Memo.docx` or Markdown equivalent --- a concise memo communicating a relevant ongoing / improvement or completed ticket, including expected outages or inconvenience, and when needed, reminders on how to report promptly  
- `06_Preventive_Maintenance_Checklist.md` --- If necessary to prevent .  
If file creation is available, create the files. If not, output each artifact in a separate clearly named section that can be saved as a file.  
**4. Documentation and communication standards**  
Use plain English suitable for a Philippine small-business workplace.  
   
 Explain technical terms briefly. Keep the manager report concise and factual. Separate:  
- observed facts;  
- diagnostic assumptions;  
- actions actually demonstrated in the lab;  
- recommended actions not yet performed.  
Use dates in `DD MMM YYYY` format, 24-hour time, and Philippine peso notation only if a cost example is genuinely needed.  
**5. Quality checks**  
Before finalizing, check that:  
- every runbook has a safe stopping point and escalation criteria;  
- no sample password, API key, or real personal data appears;  
- ticket details agree with the report and memo;  
- instructions are suitable for an IT-Officer-in-Charge, in case when the issue needs to be resolved immediately by the next-person-in-charge with minimal technical ability; and do not overstate certainty;  
- every action is distinguishable as proposed, or requiring approval;  
- filenames and headings are consistent.  
Return a brief file inventory and a **5-minute reviewer walkthrough** at the end.  
