# Local LLM Chatbot using Ollama & Gemma 2B 🚀

A lightweight Generative AI chatbot built using **LangChain**, **Ollama**, **Gemma 2B**, and **Streamlit**.
This project demonstrates how to run a fully local Large Language Model (LLM) without relying on paid cloud APIs.

---

# ✨ Features

* Local LLM integration with Ollama
* Gemma 2B model support
* Streamlit-based UI
* LangChain prompt pipeline
* Fast and lightweight setup
* No external API billing

---

# 🛠️ Tech Stack

* Python
* LangChain
* Ollama
* Streamlit
* Gemma 2B

---

# 📂 Project Structure

```bash id="m8q2vk"
1.2-ollama/
│
├── app.py
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash id="x5q9wc"
git clone <your-repository-url>
```

---

## 2️⃣ Navigate to Project Directory

```bash id="u1p4tx"
cd <project-folder>
```

---

## 3️⃣ Create Virtual Environment

```bash id="r7m8qp"
conda create -p venv python=3.13 -y
```

---

## 4️⃣ Activate Environment

```bash id="f2m5vk"
conda activate ./venv
```

---

## 5️⃣ Install Dependencies

```bash id="k9q2wc"
pip install -r requirements.txt
```

---

# 🤖 Install Ollama Model

Pull the Gemma 2B model locally:

```bash id="v4m8tx"
ollama pull gemma:2b
```

Verify installation:

```bash id="p6q1vk"
ollama list
```

---

# ▶️ Run the Application

```bash id="x3m7wc"
streamlit run app.py
```

---

# 🌐 Access the App

Open in your browser:

```text id="m1v4tx"
http://localhost:8501
```

---

# 📌 Notes

* Ensure Ollama is installed and running before starting the app.
* The application runs completely locally.
* No OpenAI API key is required.

---

# 👨‍💻 Author

**Alokit Mishra**
