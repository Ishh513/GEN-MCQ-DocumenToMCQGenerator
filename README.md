# 📘 Document to MCQ Generator

## 🚀 Overview

The **Document to MCQ Generator** is a Python-based application that automatically converts textual content (documents, PDFs, or plain text) into **Multiple Choice Questions (MCQs)** using Natural Language Processing (NLP) techniques.

This project helps students, teachers, and EdTech platforms generate quizzes instantly from study materials, reducing manual effort and saving time.

---

## 🎯 Features

* 📄 Accepts text input or documents
* 🤖 Automatic MCQ generation using NLP
* 🧠 Smart question and answer extraction
* 🔢 Generate customizable number of questions
* 📊 Structured MCQs (Question + Options + Answer)
* ⚡ Fast and easy to use

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** pdfplumber,docx,werkzeug.utils,fpdf (based on implementation)
* **Framework (Optional):** Flask 
* **AI/NLP:** Text processing and question generation

---

## 📂 Project Structure

```
GEN-MCQ-DocumenToMCQGenerator/
│── app.py / main.py        # Main application
│── mcq_generator.py        # Core MCQ logic
│── utils.py                # Helper functions
│── requirements.txt        # Dependencies
│── README.md               # Documentation
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Ishh513/GEN-MCQ-DocumenToMCQGenerator.git
cd GEN-MCQ-DocumenToMCQGenerator
```

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run the Application

```bash
python app.py
```

### OR (if using Streamlit)

```bash
streamlit run app.py
```

### Steps to Use

1. Input or upload document/text
2. Choose number of MCQs
3. Click Generate
4. View generated MCQs

---

## 📸 Example Output

```
Q1. What is Artificial Intelligence?
a) Machine learning method  
b) Simulation of human intelligence  
c) Programming language  
d) Database system  

Answer: b) Simulation of human intelligence
```

---

## 💡 Use Cases

* 📚 Students for exam preparation
* 👩‍🏫 Teachers for quiz creation
* 🎓 Educational platforms
* 🧪 Practice test generation

---

## 🔮 Future Enhancements

* Difficulty levels (Easy/Medium/Hard)
* PDF & DOCX upload support
* Export MCQs to PDF/CSV
* Improved UI
* Multi-language support

---

## 🤝 Contributing

Contributions are welcome!
Fork the repository and create a pull request.
