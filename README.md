
📝 AI Resume Optimiser and Generator
📌 Overview
This is an AI-powered Resume Optimiser and Generator that takes:

Input: Candidate resume (PDF/DOCX) and a target job description (plain text)
Output: An optimised resume tailored to the job description with:
Missing keywords intelligently integrated into relevant sections
Original formatting preserved (for DOCX resumes)
ATS (Applicant Tracking System) compatibility enhancements
A brief change log explaining modifications
The goal is to increase your chances of passing ATS screening and align your resume more closely with the job requirements.

Features:
Prompt design: Interactive prompts request resume and job description filenames from the user
Multi-format support: Handles .docx and .pdf resumes
Resume parsing and editing automation: Automatically reads resumes, detects missing keywords, and integrates them into the correct sections
Job-market keyword optimisation: Extracts job description keywords and places them where they naturally fit (Skills, Experience, Projects)
Formatting preservation: Keeps the original DOCX layout intact
Change log generation: Outputs a change_log.txt summarising what was added and where

Skills Tested:

Prompt Design
Resume Parsing (PDF/DOCX)
Automated Editing
ATS / Job-Market Keyword Optimisation
Formatting Preservation
Logging and Change Tracking

Folder Structure:

resume_optimizer/
│
├── main.py Main script
├── resume.docx or resume.pdf (input resume)
├── job_desc.txt Target job description (text)
├── optimised_resume.docx Optimised output resume
├── change_log.txt Summary of changes
└── README.md Project documentation

Setup Instructions:

Install Python
Download from python.org and install
Check installation with:
python --version

Install VS Code (optional)
Download from code.visualstudio.com and open your project folder

Install Required Packages
In the terminal:
pip install python-docx pdfplumber

Prepare Files:
Place your resume file (resume.docx or resume.pdf) in the project folder
Create job_desc.txt and paste the job description inside
How to Run:
Open VS Code terminal inside the folder
Run:python main.py
Enter:Resume filename (with extension)
Job description filename (job_desc.txt)
The script will:
Parse the resume
Extract keywords from job description
Find and insert missing keywords into relevant sections
Save the results

Outputs:
optimised_resume.docx
Your ATS-optimised resume with keywords added intelligently to the correct sections, formatting preserved for DOCX sources

change_log.txt
Lists what keywords were added and in which section

Example:
Added to Skills: Django, REST APIs, AWS
Added to Experience: collaborated, optimised
Added to Projects: cloud

Notes:

DOCX resumes preserve their formatting 100%
PDF resumes are supported but may lose complex layouts after conversion to DOCX
Keywords are placed in relevant sections, not simply appended as a bulk list
Future Enhancements
Use NLP for smarter keyword classification and insertion
Preserve full PDF formatting with OCR/template mapping
Export directly to PDF format
Add GUI or web-based interface
License:This project is open-source for educational and personal use

Author:Veeramachineni Likhitha



