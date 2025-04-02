# ATS---Applicant-Tracking-System-checker

Overview
ATS (Applicant Tracking System) Resume Expert is an AI-powered tool that analyzes resumes against job descriptions using Google's Gemini API. It provides:
Resume Analysis: Evaluates how well a resume aligns with a given job description.
ATS Optimization: Checks for missing keywords and provides suggestions.
Match Percentage: Computes the resume-job description match score.


🚀 Features
✅ Uses Google Gemini AI for intelligent resume analysis.

✅ Converts PDF resumes into images for AI processing.

✅ Provides detailed feedback on strengths, weaknesses, and missing keywords.

✅ Built using Streamlit for an interactive UI.

🛠️ Requirements
Before running the project, install the following dependencies:
```
pip install streamlit google-generativeai python-dotenv pdf2image
```

🔧 Setup Instructions
1️⃣ Clone the Repository
```
git clone https://github.com/your-username/ats-resume-expert.git
cd ats-resume-expert
```

2️⃣ Set Up Environment Variables
Create a .env file in the project root and add your Google API key:
```
GOOGLE_API_KEY=your_api_key_here
```

3️⃣ Run the Application
```
streamlit run app.py
```

📜 How It Works
Upload your resume (PDF format).

Enter the job description.

Click the analysis button to get AI-powered insights.

View the match percentage, missing keywords, and improvement suggestions.


🤝 Contributing
Feel free to submit issues or pull requests!





