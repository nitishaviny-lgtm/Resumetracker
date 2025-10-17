Resume & Skill Matching System
The Resume & Skill Matching System is an automated tool designed to help HR professionals quickly evaluate resumes and match candidates’ skills with job descriptions. This project leverages Python, Natural Language Processing (NLP), and regular expressions to extract and analyze candidate information efficiently.

It calculates a resume score based on how well a candidate’s skills, certifications, and projects align with the job requirements, helping recruiters shortlist the best candidates faster.

Features

Extracts personal information from resumes:

Name

Email address

Phone number

Extracts technical skills and certifications such as Python, Java, SQL, HTML, CSS, and Cyber Security.

Matches extracted skills with a job description file.

Computes a resume score based on skill match and relevance.

Supports PDF resume input.

Technologies Used

Python 3.x

PyPDF2: For reading and extracting text from PDF resumes.

Regular Expressions: For identifying email IDs, phone numbers, and other structured data.

Nspacy (NLP Library): For processing and extracting English words and keywords from resumes and job descriptions.

How It Works

PDF Resume Parsing:

Reads the PDF file and extracts text from all pages.

Information Extraction:

Extracts personal details (name, email, phone).

Extracts technical skills and certifications using keyword matching and NLP.

Job Description Matching:

Compares extracted skills with required skills in the job description.

Measures similarity and calculates a match score.

Resume Scoring:

Combines the extracted data and matching results into a numerical score to rank candidates.

Usage

Place resume PDFs in the designated folder.

Provide a job description file (text or PDF).

Run the Python script:

python resume_skill_matcher.py


View the resume scores and extracted candidate information.

Future Enhancements

Add support for multiple file formats (DOCX, TXT).

Integrate a GUI for easy HR use.

Implement machine learning to improve skill matching and scoring accuracy.

Include experience, education, and project relevance in scoring.

Benefits

Saves recruiters significant time in shortlisting candidates.

Provides objective scoring for skill and project relevance.

Can be adapted for any domain or job role.
