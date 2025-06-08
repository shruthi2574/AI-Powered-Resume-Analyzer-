🧠 AI-Powered Resume Analyzer
An intelligent, interactive tool built with Python to analyze your resume against a job description. It extracts key skills and keywords from both inputs and calculates a match score, helping job seekers tailor their resumes to specific job roles.

---

## 🔍 Features

- 📄 **Upload Resume**: Extracts text from PDF resume files  
- 🧾 **Input Job Description**: Manually enter the job description  
- 🔎 **Keyword Matching**: Identifies common and missing keywords  
- 📊 **Match Score**: Calculates a resume-job description relevance score  
- 💡 **Suggestions**: Recommends keywords to improve your resume


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

- Python 3.x (if running locally)  
- Google Colab (recommended for ease of use)  
- Resume in `.pdf` format  

### Installation & Execution

You can run the project in Google Colab:

1. **Install the required libraries:**

    ```python
    !pip install nltk
    !pip install PyMuPDF
    ```

2. **Upload your resume:**

    ```python
    from google.colab import files  
    uploaded = files.upload()
    ```

3. **Paste the job description** when prompted.

4. **The script will output:**

    - ✅ Matching keywords  
    - 🧩 Missing skills  
    - 📊 Resume match score


---
## 💡 Example Output

📋 **Job Description**:  
We are hiring a software engineer with experience in Python, APIs, Machine Learning, SQL, and version control tools like Git.

✅ **Matching Keywords**:  
`python`, `machine`, `learning`, `sql`, `git`

📈 **Resume Match Score**:  
`83.33%`

🔍 **Suggested Skills or Keywords to Improve**:  
`apis`, `control`, `tools`, `version`


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

