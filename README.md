# 📄 Resume Analyzer based on Job Description (JD)

An intelligent resume screening tool using Python, OCR (Tesseract), NLP, and Gradio. It extracts text from resumes (PDF/image), compares with job descriptions, and outputs:

- ✅ Best-fit roles based on matched skills  
- 📊 ATS (Applicant Tracking System) score as a pie chart  
- 📌 Suggestions to improve your resume for better shortlisting chances  

---

## 🔧 Features

- Extracts text from resume PDFs using OCR (`pytesseract`)
- Tokenizes and filters job description to extract keywords
- Compares extracted skills with predefined skills for 10 tech roles
- Calculates ATS score based on matched skills
- Displays result in a pie chart and gives role suggestions
- Interactive UI using **Gradio**

---

## 💼 Supported Job Roles

- AI/ML Intern  
- Data Analyst  
- Web Developer  
- Backend Developer  
- Cloud Engineer  
- DevOps Engineer  
- Cybersecurity Analyst  
- Data Scientist  
- Business Analyst  
- Full Stack Developer  

---

## 📌 Requirements

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
