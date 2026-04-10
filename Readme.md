# 📝 Text Summarization App

A web-based application that generates concise and meaningful summaries from long text using Natural Language Processing (NLP) techniques and transformer-based models.

## 🚀 Features

- Automatic text summarization  
- Handles long paragraphs and documents  
- Fast and efficient processing  
- Simple and user-friendly interface  
- Powered by transformer models (T5/BART)  

## 🛠️ Tech Stack

- Frontend: HTML, CSS  
- Backend: Python, FastAPI  
- Machine Learning: Hugging Face Transformers  
- Model: T5 / BART 

## 📂 Project Structure

    textsummarizeapp/
    │
    ├── app.py
    ├── index.html
    ├── static/
    ├── saved_summary_model/
    ├── requirements.txt
    └── README.md
## ⚙️ Installation & Setup


### 1. Clone the Repository

```bash
git clone https://github.com/nikitachanda13/textsummarizeapp.git
cd textsummarizeapp
```
### 2.Create a Virtual Environment
```bash
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows
```
### 3.Install Dependencies
```bash
pip install -r requirements.txt
```


▶️ Running the Application
```bash
uvicorn app:app --reload
```

### 🧠 How It Works
- User enters input text
- Backend processes it using NLP model
- Model generates summary
- Summary is displayed

### 📌 Future Enhancements
- PDF/DOCX upload support
- Multi-language summarization
- Extractive + abstractive modes
- Cloud deployment






