# 💼 Smart Resume Analyser using NLP
A smart web-based resume analysis tool that leverages Natural Language Processing (NLP) to automatically extract, analyze, and match candidate resumes to job profiles. Built using Python, spaCy, and Flask, this project streamlines the recruitment process by providing quick insights into applicant skillsets.

# 🚀 Features
📄 Resume Upload: Supports PDF and DOCX formats

# 🧠 NLP Analysis: Extracts skills, education, and experience using spaCy

# 🎯 Job Role Matching: Maps resumes to job profiles based on keywords

# 📊 Skill Classification: Identifies candidate’s skill domain (e.g., Data Science, Web Dev)


# 📁 Admin Dashboard: View and manage uploaded resumes and their analyses

# 📸 Demo


# 🛠️ Tech Stack
Technology	Description
Python	Core programming language
Flask	Web framework
spaCy	NLP library for parsing and analysis
HTML/CSS	Frontend layout and styling
Bootstrap	UI components and responsiveness
# ⚙️ How It Works
User uploads a resume (PDF/DOCX)

spaCy processes the text and extracts key information

Skills are matched against predefined role-specific keywords

Candidate is classified into a relevant job domain

Result is displayed on the dashboard with key highlights

# 🧩 Installation & Setup
Clone the repository
bash
Copy
Edit
git clone https://github.com/Sanchit2104/Smart-Resume-Analyser-using-NLP.git
cd Smart-Resume-Analyser-using-NLP
Create a virtual environment (recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
Run the app
bash
Copy
Edit
python app.py
Visit http://localhost:5000 in your browser.

# 📁 Folder Structure
php
Copy
Edit
├── app.py                   # Main Flask application
├── templates/               # HTML files
├── static/                  # CSS, JS, assets
├── Uploads/                 # Uploaded resumes
├── requirements.txt         # Python dependencies
├── ResumeParser.py          # NLP logic and resume processing
└── README.md
# 🛡️ Future Improvements
🔐 File validation and security checks

📈 Resume-job matching score

📬 Email notifications to applicants

🐳 Docker containerization for deployment

🧪 Unit tests for better reliability
