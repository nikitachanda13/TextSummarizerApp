# 📝 Text Summarization App

A web-based application that generates concise and meaningful summaries from long text using Natural Language Processing (NLP) techniques and transformer-based models.

---

## 🚀 Features

- 🔹 Automatic text summarization  
- 🔹 Handles long paragraphs and documents  
- 🔹 Fast and efficient processing  
- 🔹 Simple and user-friendly interface  
- 🔹 Powered by transformer models (T5/BART)  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript 
- **Backend:** Python, FastAPI  
- **Machine Learning:** Hugging Face Transformers  
- **Model:** T5 / BART  

---

## 📂 Project Structure
textsummarizeapp/
│
├── app.py # FastAPI backend
├── index.html # Frontend UI
|
├── saved_summary_model/ # Trained model files
├── requirements.txt # Dependencies
└── README.md # Documentation

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/nikitachanda13/TextSummarizerApp.git
cd  TextSummarizerApp


### 2. Create a Virtual Environment
python -m venv .venv
source .venv/bin/activate   # For Mac/Linux
.venv\Scripts\activate      # For Windows
### 3. Install Dependencies
pip install -r requirements.txt

▶️ Running the Application
uvicorn app:app --reload
Open your browser and visit:
http://127.0.0.1:8000

### 🧠 How It Works
1.User enters input text in the web interface
2.The request is sent to the FastAPI backend
3.The NLP model processes the text
4.A summarized version is generated and returned
5.The summary is displayed to the user
