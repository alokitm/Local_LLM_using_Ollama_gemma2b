# Local LLM using Ollama & Gemma 2B 🚀

A simple GenAI chatbot built using **LangChain**, **Ollama**, **Gemma 2B**, and **Streamlit**.

---

# 🛠️ Tech Stack

* Python
* LangChain
* Ollama
* Streamlit
* Gemma 2B

---

# ⚙️ Setup

## Clone Repository

```bash id="m8q2vk"
git clone https://github.com/alokitm/GenAI.git
```

---

## Create Environment

```bash id="x5q9wc"
conda create -p venv python=3.13 -y
```

---

## Activate Environment

```bash id="u1p4tx"
conda activate ./venv
```

---

## Install Requirements

```bash id="r7m8qp"
pip install -r requirements.txt
```

---

# 🤖 Install Ollama Model

```bash id="f2m5vk"
ollama pull gemma:2b
```

---

# ▶️ Run Application

```bash id="k9q2wc"
cd 1-Langchain/1.2-ollama
```

```bash id="v4m8tx"
streamlit run app.py
```

---

# 🌐 Open Browser

```text id="p6q1vk"
http://localhost:8501
```

---

# 👨‍💻 Author

Alokit Mishra
