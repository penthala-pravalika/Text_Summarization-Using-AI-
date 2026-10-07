# 📝 Text Summarization App

A simple **AI-powered Text Summarization application** built with **Python, Streamlit, and Hugging Face Transformers**.

The application can summarize:

* ✍️ Pasted text
* 📄 `.txt` files
* 📕 `.pdf` files

It uses pretrained **BART-based abstractive summarization models** and runs locally without requiring an API key.

---

## 🚀 Features

* 📝 Summarize long text
* 📄 Upload `.txt` files
* 📕 Upload `.pdf` files
* 🤖 Choose between two pretrained models
* ⚡ Fast summarization with DistilBART
* 🎯 Better-quality summaries with BART Large
* 📏 Choose summary length:

  * Short
  * Medium
  * Long
* 📊 Displays original and summarized word counts
* 📈 Shows percentage reduction
* ⬇️ Download the generated summary
* 🔒 No API key required
* 💻 Runs locally

---

## 🤖 Models Used

The application provides two Hugging Face models:

### 1. DistilBART

```text
sshleifer/distilbart-cnn-12-6
```

* Faster
* Lightweight
* Suitable for normal laptops
* Good for quick summarization

### 2. BART Large

```text
facebook/bart-large-cnn
```

* Better summarization quality
* Larger model
* Requires more RAM and processing time

---

## 🛠️ Technologies Used

| Technology                | Purpose               |
| ------------------------- | --------------------- |
| Python                    | Programming language  |
| Streamlit                 | Web application UI    |
| Hugging Face Transformers | NLP and summarization |
| PyTorch                   | Model execution       |
| PyPDF                     | PDF text extraction   |
| BART / DistilBART         | Text summarization    |

---

## 📂 Project Structure

```text
Text_Summarization/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/text-summarization.git
```

Move into the project directory:

```bash
cd text-summarization
```

---

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

Create a `requirements.txt` file:

```text
streamlit
transformers
torch
pypdf
sentencepiece
```

You can install everything using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser.

Usually, Streamlit runs at:

```text
http://localhost:8501
```

---

## 🧑‍💻 How to Use

### Step 1 — Select a Model

From the sidebar, choose:

```text
DistilBART (faster, lighter)
```

or

```text
BART Large (better quality)
```

### Step 2 — Select Summary Length

Choose:

* **Short** — concise summary
* **Medium** — balanced summary
* **Long** — more detailed summary

### Step 3 — Select Input Type

Choose either:

```text
Paste text
```

or

```text
Upload file
```

### Step 4 — Provide Text

You can paste an article, notes, report, or other text.

For files, upload:

```tex
```
