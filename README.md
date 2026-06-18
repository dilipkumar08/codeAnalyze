# 🚀 Code Analyzer AI

> Understand any code instantly with AI-powered explanations, error detection, complexity analysis, and output prediction.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green.svg)
![HuggingFace](https://img.shields.io/badge/HuggingFace-AI-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-orange.svg)

---

## 🎯 Overview

Code Analyzer AI is a web-based application that helps developers understand unfamiliar code quickly.

Simply paste your code, select the programming language, and receive:

✅ Purpose of the code

✅ Line-by-line explanation

✅ Potential errors and bugs

✅ Expected output

✅ Time complexity analysis

✅ AI-generated code review

---

## ✨ Features

### 🧠 AI-Powered Analysis

Uses Hugging Face Inference API to generate intelligent explanations.

### 📖 Code Understanding

Explains:

- What the code does
- How it works
- Why it works

### 🐞 Error Detection

Identifies:

- Syntax errors
- Logical errors
- Bad practices

### ⚡ Complexity Analysis

Provides:

- Time Complexity
- Performance insights

### 🌐 Web Interface

Built using:

- FastAPI
- HTML
- CSS
- JavaScript

### 📝 Logging

Tracks:

- Requests
- Processing status
- Errors
- Execution details

---

## 📸 Application Flow

```text
┌────────────────────┐
│      Home Page     │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ Launch Analyzer    │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ Enter Code         │
│ Select Language    │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ Process Request    │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ AI Analysis Result │
└────────────────────┘
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| FastAPI | Backend API |
| Python | Core Logic |
| Hugging Face | AI Model |
| HTML/CSS | Frontend |
| JavaScript | API Communication |
| Logging | Monitoring |

---

## 📂 Project Structure

```text
code-analyzer/
│
├── backend/
│   ├── app.py
│   ├── main.py
│   ├── logger.py
│   ├── model.py
│   └── app.log
│
├── frontend/
│   ├── home.html
│   └── analyze.html
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/<username>/code-analyzer.git

cd code-analyzer
```

### Create Virtual Environment

```bash
python -m venv venv
```

Linux/Mac

```bash
source venv/bin/activate
```

Windows

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file:

```env
HF_TOKEN=your_huggingface_token
```

---

## ▶️ Running the Application

```bash
uvicorn app:app --reload
```

Open:

```text
http://localhost:8000
```

---

## 📝 Example

### Input

```python
def add(a, b):
    return a + b

print(add(2,3))
```

### Output

```text
Purpose:
Adds two numbers.

Line By Line:
- Function definition
- Returns sum
- Prints result

Output:
5

Time Complexity:
O(1)

Potential Errors:
None
```

---

## 📊 Logging

Logs are automatically written to:

```text
app.log
```

Example:

```text
2026-06-18 18:44:12 | INFO | Analysis started
2026-06-18 18:44:16 | INFO | Analysis completed
```

---

## 🔮 Future Improvements

- Dark Mode
- Code Syntax Highlighting
- Download Analysis as PDF
- Multiple AI Models
- User Authentication
- Analysis History
- Docker Deployment
- Cloud Hosting

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Create Pull Request

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork it

🧑‍💻 Share it with fellow developers

---

## 👨‍💻 Author

**Dilip Kumar**

Built with ❤️ using FastAPI and Hugging Face.
