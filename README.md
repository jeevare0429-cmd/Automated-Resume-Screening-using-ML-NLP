# Automated-Resume-Screening-using-ML-NLP
📌 Project Overview

This project automates the process of resume screening using Machine Learning (ML) and Natural Language Processing (NLP). Instead of manually filtering resumes, the system analyzes candidate CVs, extracts relevant information, and ranks applicants based on their skills, experience, and job requirements.

It helps recruiters save time, reduce human bias, and quickly identify the most suitable candidates.

⚙️ Features

📝 Resume Parsing – Extracts text from resumes (PDF/DOCX).

🔍 Keyword Matching – Compares resumes with job descriptions.

🤖 ML/NLP Models – Uses TF-IDF, Word Embeddings, or BERT for text analysis.

📊 Candidate Ranking – Scores resumes and provides a ranking list.

📂 Dashboard (optional) – Visualizes candidate matching results.

🛠️ Tech Stack

Languages: Python

Libraries:

pandas, numpy – data handling

scikit-learn – ML models (e.g., Logistic Regression, Random Forest, SVM)

NLTK / spaCy – NLP processing

PyPDF2, docx2txt – resume text extraction

Optional: Flask/Streamlit for UI

📑 Workflow

Data Collection – Gather resumes (PDF/DOCX) and job descriptions.

Preprocessing – Clean, tokenize, and normalize text.

Feature Extraction – TF-IDF / embeddings for vector representation.

Model Training – Train ML/NLP model to classify or rank resumes.

Evaluation – Accuracy, Precision, Recall, F1-score.

Output – Ranked list of candidates best matching the job profile.

🚀 How to Run


Install dependencies:

pip install -r requirements.txt


Run the script:

python main.py


Upload resumes and job description → get ranked candidates.

📈 Results

Faster resume screening compared to manual process.

Improved accuracy in candidate-job matching.

Flexible to adapt to different domains (IT, Finance, Healthcare, etc.).

🔮 Future Enhancements

Use BERT / Transformer models for better semantic understanding.

Integrate with ATS systems for real-time screening.

Add web dashboard for recruiters.

👨‍💻 Author

Developed by Jeevanandh M – Passionate about AI, NLP, and Recruitment Tech.
