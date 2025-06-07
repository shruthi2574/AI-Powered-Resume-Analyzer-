🧠 AI-Powered Resume Analyzer
An intelligent, interactive tool built with Python to analyze your resume against a job description. It extracts key skills and keywords from both inputs and calculates a match score, helping job seekers tailor their resumes to specific job roles.

---

🔍 Features

<br>
📄 Upload and extract text from your resume (PDF format)

🧾 Input job descriptions manually

🔎 Identifies matching and missing keywords

📊 Calculates a resume-job match score

💡 Suggests keywords to improve your resume relevance

---

## 🧰 Tech Stack

| Tool         | Purpose                                      |
|--------------|----------------------------------------------|
| Python       | Core programming language                    |
| NLTK         | Text tokenization and stopword removal       |
| PyMuPDF      | Extract text from PDF files                  |
| Google Colab | Cloud-based execution and file upload        |
| Git & GitHub | Version control and collaboration            |

---

## 🚀 Getting Started

### Prerequisites
Python 3.x (if running locally)

Google Colab (recommended for ease of use)

Resume in .pdf format

⚙️ Installation & Execution
<br>
You can run the project in Google Colab:
<br>

1.Install the required libraries:

  !pip install nltk
  <br>
  !pip install PyMuPDF
  <br>
2.Upload your resume:

from google.colab import files
uploaded = files.upload()

3.Paste the job description when prompted.

4.The script will output:

✅ Matching keywords

📉 Missing skills

📈 Resume match score

---

💡 Example Output
<br>

📋 Paste the job description below:
We are hiring a software engineer with experience in Python, APIs, Machine Learning, SQL, and version control tools like Git.

✅ Matching Keywords:
python, machine, learning, sql, git

📈 Resume Match Score: 83.33%

🔍 Suggested Skills or Keywords to Improve:
apis, control, tools, version

---

## 📂 Project Structure

```
resume-analyzer/
├── resume_analyzer.ipynd
└── README.md
```

---

## 🙋‍♀️ Author

**Gugulothu Shruthi**  
B.Tech,CSE—Narayanamma Institute of Technology  
✉️ [gugulothushruthi@gmail.com](mailto:gugulothushruthi@gmail.com)

---

