# AI-Assisted IT Troubleshooting Guide Creation

## Project Overview

This project demonstrates the practical use of generative AI to transform sanitized IT support notes into a clear, concise, and user-friendly troubleshooting guide for non-technical employees.

The project focuses on a recurring workplace task: converting short technical notes into simple instructions while preserving privacy, factual accuracy, and human oversight.

The project was completed as part of the **AI Fundamentals for the Workplace** training program at **SDAIA Academy**.

---

## Project Objective

The main objective is to use an AI assistant responsibly to:

- Convert technical IT support notes into simple workplace instructions.
- Apply the **R.A.C.E. prompt framework**: Role, Action, Context, and Expectation.
- Refine the first AI-generated draft through an iterative follow-up prompt.
- Protect personal and confidential information through data masking.
- Verify the final output manually before use.
- Estimate the time saved by using AI for a recurring documentation task.

---

## Use Case

### Target Task

Create a concise workstation sign-in troubleshooting guide from sanitized technical support notes.

The guide helps a non-technical employee check basic sign-in issues before contacting IT support.

### Sanitized Input

The input includes only general troubleshooting steps such as:

- Confirming the workstation is connected to the network.
- Checking Caps Lock before entering a password.
- Restarting the workstation.
- Using an updated password after a recent password change.
- Contacting IT support if the issue continues.

No employee names, usernames, passwords, account IDs, company names, internal system names, customer data, or confidential organisational information are included.

---

## AI Workflow

The project follows this workflow:

**Sanitized IT Notes → R.A.C.E. Prompt → Initial AI Output → Follow-up Refinement → Final Output → Human Verification**

The first AI response is treated as a draft. A follow-up prompt is then used to simplify the language and improve readability while keeping the original facts unchanged.

---

## R.A.C.E. Prompt Framework

### Role
The AI acts as an IT support documentation specialist.

### Action
The AI converts sanitized troubleshooting notes into a clear troubleshooting guide.

### Context
The task is a recurring workplace documentation activity intended for non-technical employees.

### Expectation
The final guide must be short, professional, easy to understand, and limited to the information provided.

---

## Verification and Responsible AI Use

The final output is reviewed manually against the original sanitized notes.

The verification checks that:

- All five troubleshooting instructions are preserved.
- No unsupported technical procedures are added.
- No personal or confidential information appears.
- The escalation instruction remains correct.
- Human review remains responsible for final approval.

AI is used only to assist with drafting and simplification. It is not used to make decisions about users, accounts, or access permissions.

---

## Estimated Impact

The project demonstrates that AI can reduce the time needed to draft and simplify a troubleshooting guide.

**Estimated manual time:** 15 minutes  
**Estimated AI-assisted time:** 5 minutes  
**Estimated time saved:** approximately 10 minutes per guide

---

## Project Files

```text
AI-Workplace-IT-Troubleshooting-Capstone/
├── README.md
├── Renad_Alanzi_AI_Workplace_Capstone_6_PAGES_FINAL.pdf
└── screenshots/
    ├── race_prompt.png
    ├── initial_output.png
    └── refinement_final_output.png
```

---

## How to Use This Repository

No software installation or code execution is required.

1. Open the project PDF to review the complete capstone report.
2. Review the screenshots to see the structured prompt, initial AI output, and refinement process.
3. Use the documented R.A.C.E. structure as a reference for similar workplace AI tasks.
4. Always sanitize sensitive information before using an AI assistant.
5. Verify AI-generated content before using it in a workplace context.

---

## Technical Documentation

This repository documents the complete AI-assisted workflow used in the capstone:

- Task selection and suitability.
- Data masking and privacy protection.
- Structured prompt engineering using R.A.C.E.
- Initial AI-generated output.
- Iterative prompt refinement.
- Final refined output.
- Human verification.
- Estimated productivity impact.

---

## Version Control and Git Best Practices

The repository uses Git for version control.

Recommended practices:

- Use clear and descriptive commit messages.
- Keep the `main` branch stable.
- Commit meaningful changes separately.
- Use version tags for major submitted versions, such as `v1.0.0`.
- Avoid committing sensitive or confidential data.
- Keep documentation updated with project changes.

Example commit messages:

```text
docs: add professional README
docs: add final capstone report
docs: add AI workflow screenshots
chore: prepare v1.0.0 final submission
```

---

### 🔗 Training Program

This project was completed as part of the L0-FAE — AI Fundamentals for the Workplace training program at SDAIA Academy, under the supervision of Abdullah Khalid AlShahrani.

The portfolio demonstrates the practical application of AI fundamentals in the workplace through prompt engineering, professional writing, information processing, verification and fact-checking, safe and responsible use, and daily task integration.

Official SDAIA Academy GitHub:  
https://github.com/SDAIAAcademy

---

## Saudi Open-Source Community

This project supports positive participation in the Saudi technical community by encouraging developers and trainees to explore high-quality Saudi projects on GitHub, follow relevant accounts, contribute to open-source repositories when appropriate, and interact through Stars, Forks, Pull Requests, and Issues.

---

## Author

**Renad Alanzi**

Capstone Evaluation Project  
AI Fundamentals for the Workplace  
SDAIA Academy  
2026
