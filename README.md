# Filesure-internship-task

# 📝 Filesure Internship Take-Home Assignment
**Author:** Md Ripon Al Mamun  
**Role:** Python + Machine Learning Intern Applicant

---

## 📌 Overview

This repository contains my submission for the Filesure internship take-home assignment. The task involved parsing a real ROC filing (Form ADT-1), extracting structured data using Python, and generating a plain English AI-style summary.

---

## 📂 Project Structure

![image](https://github.com/user-attachments/assets/6eada775-2f1a-4b1a-8230-84485c287996)

---

## 🛠️ How to Run
1. **Install the required library** (PyMuPDF):
```bash

pip install pymupdf

    Place the input PDF file (Form ADT-1-29092023_signed.pdf) in the same directory.

    Run the script:

python extractor.py
# Outputs:

    output.json: structured data

    summary.txt: natural language summary

📄 Extracted Fields (output.json)
{
  "company_name": "ALUPA FOODS PRIVATE LIMITED",
  "cin": "U74999KA2016PTC098981",
  "registered_office": "DHANYALAXMI RICE MILL, 5-110A, PUTTUR, UDUPI, Karnataka, 576105",
  "company_email": "mail@alupafoods.in",
  "appointment_date": "2022-04-01",
  "appointment_end_date": "2027-03-31",
  "auditor_name": "MALLYA & MALLYA",
  "auditor_address": "29/2, 1st Floor, Parijatha Complex, Race Course Road, Bangalore, Karnataka, 560001",
  "auditor_email": "mallyaandmallya@gmail.com",
  "auditor_frn_or_membership": "001955S",
  "auditor_pan": "AABFM8893Q",
  "appointment_type": "Appointment/Re-appointment in AGM",
  "financial_years_covered": 5,
  "category_of_auditor": "Auditor's Firm",
  "within_20_company_limit": "Yes"
}


📜 AI-Generated Summary (summary.txt)

ALUPA FOODS PRIVATE LIMITED has appointed M/s MALLYA & MALLYA as its statutory auditor for the period from
1 April 2022 to 31 March 2027 via AGM resolution. The appointment was disclosed through Form ADT-1, along with
attachments including the auditor’s consent, board resolution, intimation letter, and acceptance
letter – confirming full compliance with MCA regulations.

🎥 Demo Video


✅ Assumptions & Notes

    Auditor and company details were clearly visible in the form.

    Attachments (Consent Letter, Board Resolution, etc.) were reviewed manually and summarized in the AI output.

    Form ADT-1 was processed using PyMuPDF, which performed well for this task.

👤 About Me

Md Ripon Al Mamun
📞 +8801880807962
🔗 LinkedIn
🔗 GitHub


🧪 Evaluation Criteria Coverage

| Requirement                            | Status  |
| -------------------------------------- | ------  |
| ✅ Accurate data extraction            | ✔️     |
| ✅ Clean JSON format                   | ✔️     |
| ✅ Human-readable AI summary           | ✔️     |
| ✅ Clean, readable, commented code     | ✔️     |
| 🌟 Bonus: Attachment insights included | ✔️     |
