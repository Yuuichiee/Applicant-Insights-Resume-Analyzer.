# 🤖 Applicant Insights Resume Analyzer

This is a **Streamlit-based 🤖 Applicant Insights Resume Analyzer** built using Python. It allows users to upload their resumes in PDF format and instantly analyzes them using **Natural Language Processing (NLP)** techniques. The goal is to help individuals evaluate their resumes based on skills, keywords, and overall strength.

## 🚀 Features

- 📤 Upload resumes in PDF format
- 🔍 Extract and analyze candidate information
- 🧠 Detect key technical and soft skills
- 📊 Evaluate resume score based on skill match
- 💾 Stores resumes in a local SQLite database
- 👤 Admin login for secure access
- 🌐 Clean and user-friendly Streamlit interface

## 🔧 Technologies Used

- Python 3
- Streamlit
- PDFMiner (for PDF parsing)
- spaCy (for NLP)
- SQLite (for storing uploaded resumes)
- Pandas

## 📂 Folder Structure
Resume flow/
│
├── app.py # Main Streamlit app
├── resumeParser.py # NLP processing functions
├── Admin.py # Admin interface
├── create_user.py # SQLite DB setup
├── style.css # Custom styles (if used)
├── Uploaded_Resumes/ # Folder where uploaded PDFs are stored
├── user.db # SQLite database
└── README.md # Project documentation


## 💻 How to Run


# Step 1: Clone the repo
https://github.com/Yuuichiee/Applicant-Insights-Resume-Analyzer..git

# Step 2: Navigate into the folder
cd smart-resume-analyzer

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the Streamlit app
streamlit run app.py



📬 Future Improvements

Add job role-based resume recommendations

Integrate with LinkedIn or other job APIs

Deploy on the cloud (Heroku, Render, etc.)

Export analysis as a downloadable report


🧑‍💼 Use Case

This tool can be useful for:

Students improving resumes before job applications

Placement cells for shortlisting candidates

Job seekers optimizing their resumes for ATS systems


