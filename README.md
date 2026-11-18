
# FinTech Zero-Shot AI Assistant

### Applied Generative AI | Prompt Engineering | FinTech

**Institution:** Chitkara University  
**Program:** BBA FinTech  
**Lab:** 1 — Zero-Shot Prompting  
**Student:** [Full Name]  
**Student ID:** [ID]  
**Academic Session:** 2026–2027  
**AI Tool/Model:** [Tool and model used]  
**Status:** Educational Prototype

---

## 1. Executive Summary

This project demonstrates the application of zero-shot prompt engineering to four realistic FinTech business workflows:

1. EMI explanation and financial calculation verification.
2. Customer complaint classification and triage.
3. Evidence-based financial data summarization.
4. Multilingual customer communication and professional email drafting.

The project uses no-code Generative AI tools, manual verification, and documented evaluation procedures.

**Project Goal:** Explore how structured prompts can improve the clarity, reliability, and usefulness of AI-generated outputs in financial services.

## 2. Business Problem

FinTech organizations handle large volumes of customer questions, payment complaints, financial information, and operational communications.

Generative AI may assist employees with these activities, but incorrect calculations, misleading statements, and unsupported assumptions create business risks.

This project investigates whether carefully designed zero-shot prompts can support these workflows while maintaining human oversight.

## 3. Project Objectives

- Develop precise zero-shot prompts.
- Apply prompt engineering to financial services.
- Verify AI-generated financial calculations.
- Classify fictional customer complaints.
- Identify hallucinations and unsupported conclusions.
- Evaluate multilingual communication accuracy.
- Document reproducible experiments.
- Follow responsible AI principles.

## 4. Methodology

For each experiment:

1. Identify the business problem.
2. Create an initial zero-shot prompt.
3. Execute the prompt using an AI tool.
4. Record the original AI response.
5. Independently evaluate the response.
6. Improve the prompt.
7. Execute the revised prompt.
8. Compare the results.
9. Document observations and limitations.

No worked examples are supplied inside the zero-shot prompts.

## 5. Lab Experiments

### Task 1: EMI Explanation and Verification

**Business Application:** Customer financial education and loan information.

**Baseline Prompt:**

> Explain EMI to a first-year BBA FinTech student in 50 words.

**Improved Prompt:**

[Paste your revised prompt for a ₹2,50,000 personal loan at 14% annual interest over 24 months.]

The improved prompt should request:

- EMI formula
- Monthly EMI
- Total repayment
- Total interest
- Tabular output

**Independent Verification**

EMI formula:

EMI = P × r × (1 + r)^n / [(1 + r)^n − 1]

Where:

- P = ₹2,50,000
- r = 0.14 / 12
- n = 24 months

Spreadsheet formula:

`=250000*(14%/12)*(1+14%/12)^24/((1+14%/12)^24-1)`

**Record Results:**

| Metric | AI Result | Spreadsheet Result | Difference |
|---|---|---|---|
| Monthly EMI | [Enter] | [Enter] | [Enter] |
| Total Repayment | [Enter] | [Enter] | [Enter] |
| Total Interest | [Enter] | [Enter] | [Enter] |

**Conclusion:** [Explain whether the AI calculations were correct.]

### Task 2: Customer Complaint Classification

**Business Application:** Customer support ticket categorization.

**Objective:** Classify eight fictional customer complaints into:

- Payments
- Loans
- KYC/Account
- Needs review

**Prompt:**

[Paste your complete zero-shot classification prompt.]

**Expected Output Format:**

| Complaint | Category | Reason | Recommended Action |
|---|---|---|---|
| [Complaint] | [Category] | [Reason] | [Action] |

**Evaluation Questions:**

1. Did the model follow the classification rules?
2. Were ambiguous complaints marked Needs review?
3. Did the model invent missing information?
4. Were recommended actions appropriate?

**Manual Review:**

[Record incorrect or disputed classifications and explain your reasoning.]

### Task 3: Evidence-Based Summarization

**Business Application:** Financial operations reporting.

**Fictional Company:** PaySetu

**Source Information:**

- September transactions: 4.2 lakh
- October transactions: 5.1 lakh
- September average transaction value: ₹640
- October average transaction value: ₹590
- Server downtime increased in October
- Revenue and cost data are unavailable

**Task:**

Generate a three-bullet factual summary and identify conclusions that cannot be supported by the source information.

**Independent Calculations:**

September transaction value:

420,000 × ₹640 = ₹26.88 crore

October transaction value:

510,000 × ₹590 = ₹30.09 crore

**Evaluation:**

| Check | Observation |
|---|---|
| Accurate transaction figures | [Enter] |
| Accurate calculations | [Enter] |
| Unsupported revenue claims | [Enter] |
| Unsupported profitability claims | [Enter] |
| Correct identification of missing data | [Enter] |

**Conclusion:** [Document actual findings.]

### Task 4: Translation and Business Communication

**Business Application:** Customer communication and settlement operations.

**Part A: Translation**

Translate the provided failed-payment notification into Hindi.

Requirements:

- Preserve the original meaning.
- Do not invent refund timelines.
- Do not add unsupported commitments.
- Back-translate into English.
- Compare the original and translated versions.

**Part B: Professional Email**

Draft a 100-word email from an operations executive to a partner bank about a delayed settlement.

Use placeholders for:

- Transaction IDs
- Amounts
- Dates
- Account references

**Evaluation:**

| Criterion | Observation |
|---|---|
| Translation accuracy | [Enter] |
| Meaning preserved | [Enter] |
| Professional tone | [Enter] |
| Word-count compliance | [Enter] |
| No invented commitments | [Enter] |

## 6. Evaluation Framework

Each task should be reviewed against the following criteria.

| Criterion | Description | Result |
|---|---|---|
| Accuracy | Correct facts and calculations | [Enter] |
| Clarity | Understandable language | [Enter] |
| Instruction Following | Compliance with requirements | [Enter] |
| Output Structure | Correct format | [Enter] |
| Responsible AI | Avoids unsupported claims | [Enter] |

**Important:** Record only actual experimental observations.

## 7. Repository Structure

```text
fintech-zero-shot-ai-assistant/
│
├── README.md
│
├── prompts/
│   ├── task-1-emi.md
│   ├── task-2-complaints.md
│   ├── task-3-summary.md
│   └── task-4-communication.md
│
├── results/
│   └── experiment-results.md
│
├── evaluation/
│   └── evaluation-log.md
│
├── screenshots/
│   └── README.md
│
└── reflection.md
```

## 8. Tools and Technologies

- Generative AI / Large Language Models
- Zero-Shot Prompt Engineering
- ChatGPT or equivalent AI tool
- Microsoft Excel or Google Sheets
- GitHub
- Markdown documentation

## 9. Responsible AI and Risk Management

This project follows these principles:

1. Use fictional customer data only.
2. Never publish banking credentials.
3. Verify numerical calculations independently.
4. Identify unsupported AI-generated claims.
5. Escalate ambiguous cases for human review.
6. Avoid making unverified financial commitments.
7. Preserve original experiment outputs.
8. Acknowledge AI assistance appropriately.

## 10. Limitations

- This is an academic prototype.
- No real banking systems are integrated.
- No live customer data is processed.
- No production deployment has been performed.
- Model performance may vary across tools and settings.
- Human verification remains necessary.

## 11. Future Scope

- Few-shot prompting experiments
- Automated complaint classification
- Structured JSON outputs
- Expanded synthetic datasets
- Prompt evaluation dashboards
- Human-in-the-loop review workflows

## 12. Reflection

**100-word reflection:**

[Explain which prompt improvement made the biggest difference, what changed in the AI output, and what you learned.]

## 13. Author

**Student Name:** [Your Name]  
**Student ID:** [Your ID]  
**Program:** BBA FinTech  
**University:** Chitkara University

## 14. Academic Integrity

This repository documents educational AI experiments.

All results, screenshots, calculations, and evaluation findings must represent genuine work. AI-generated content should be reviewed and acknowledged according to university guidelines.
