
<img width="1914" height="833" alt="Screenshot 2026-05-02 122546" src="https://github.com/user-attachments/assets/68bd3443-42d6-438c-869c-6123d0cfdd74" />
<img width="1919" height="669" alt="Screenshot 2026-05-02 153028" src="https://github.com/user-attachments/assets/352e0411-ed19-4fc2-adae-14d7b2a55af5" />

# AI Resume Screening Automation for HR

This project is an AI-powered resume screening automation workflow designed for HR teams, recruiters, and hiring departments.

The main goal of this project is to reduce manual effort in the first-level resume screening process. Instead of opening every resume manually, extracting candidate details, and comparing them with a job description, this workflow automates the process and stores the result in a structured Google Sheet.

## Project Overview

HR teams often receive many resumes through email. Manually reviewing each resume can be time-consuming and repetitive.

This workflow helps by automatically:

- Receiving resumes from Gmail
- Uploading resumes to Google Drive
- Detecting the resume file type
- Supporting PDF, Word document, and text file formats
- Extracting resume content
- Reading the job description
- Analyzing the candidate profile using AI
- Extracting structured candidate information
- Saving the final result into Google Sheets

## Key Features

- Automated resume collection from Gmail
- File upload and storage using Google Drive
- File type detection for PDF, DOC/DOCX, and TXT resumes
- Resume text extraction
- Job description extraction
- AI-based resume analysis using Google Gemini
- Structured output parsing
- Candidate strength and weakness identification
- Google Sheets integration for HR review
- Helps reduce repetitive HR screening tasks

## Tech Stack

- n8n
- Gmail
- Google Drive
- Google Sheets
- Google Gemini
- Structured Output Parser
- PDF/Text/Document extraction nodes

## Workflow Steps

1. **Resume Collection**
   - The workflow starts when a resume is received through Gmail.

2. **Upload to Google Drive**
   - The resume file is uploaded to Google Drive for storage and access.

3. **File Type Detection**
   - The workflow checks whether the resume is a PDF, Word document, or text file.

4. **Resume Content Extraction**
   - Based on the file type, the workflow extracts the text content from the resume.

5. **Job Description Processing**
   - The job description is fetched and extracted for comparison.

6. **AI Analysis**
   - Google Gemini analyzes the resume against the job description.

7. **Information Extraction**
   - The workflow extracts structured details such as:
     - First name
     - Last name
     - Email
     - Strengths
     - Weaknesses

8. **Save to Google Sheets**
   - The final structured output is appended to a Google Sheet for easy HR review.

## Output Example

The final output is stored in Google Sheets with columns such as:

| Date | Resume | First Name | Last Name | Email | Strengths | Weaknesses |
|---|---|---|---|---|---|---|

## Use Case

This project is mainly useful for:

- HR departments
- Recruiters
- Hiring managers
- Recruitment agencies
- Companies handling large numbers of resumes
- Teams looking to reduce manual resume screening time

## Benefits

- Saves HR time
- Reduces repetitive manual work
- Keeps candidate data organized
- Makes resume review faster
- Helps HR teams focus more on interviews and decision-making
- Provides structured candidate insights in Google Sheets

## Important Note

This workflow is not designed to replace HR professionals.  
It is designed to assist HR teams by automating the initial resume screening and information extraction process.

Final hiring decisions should always be made by humans.

## Screenshots

Add your workflow and Google Sheets output screenshots here.

Example:

```markdown
![Workflow Screenshot](screenshots/workflow.png)

![Google Sheets Output](screenshots/output.png)
