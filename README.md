# Text Mining & Analysis of Job Posting

## 📌 Overview
This project analyzes a job posting from **Deutsche Telekom Services Europe Czech Republic** using **text mining and NLP techniques**.  
The goal is to extract insights such as:
- Required skills and technologies
- Company culture & benefits
- Sentiment and tone of the posting
- Keyword importance and topics

The project is implemented in **Python** and can be run either as a script or inside a **Jupyter Notebook**.

---

## ⚙️ Pipeline
1. **Load Data** – Read job posting from `.docx`
2. **Preprocessing** – Clean, tokenize, lemmatize text
3. **Exploratory Data Analysis (EDA)**  
   - Word frequency  
   - Word cloud  
   - N-gram analysis  
4. **Text Mining**  
   - TF-IDF keyword extraction  
   - Named Entity Recognition (NER)  
   - Topic modeling (optional)  
5. **Sentiment Analysis** – Identify tone of the posting  
6. **Visualization** – Charts & word clouds for interpretation  
7. **Reporting** – Jupyter Notebook summary  

---

## 📦 Installation
```bash
git clone https://github.com/<your-username>/text-mining-job-posting.git
cd text-mining-job-posting
pip install -r requirements.txt
