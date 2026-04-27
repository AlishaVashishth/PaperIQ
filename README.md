# PaperIQ

**Gemini PDF Chatbot** is an AI-powered document assistant built with Streamlit that enables users to interact conversationally with one or multiple PDF documents. The system extracts, processes, and indexes document content, allowing natural-language question answering grounded strictly in the uploaded files.

Designed for research, academic reading, legal review, and knowledge management use-cases.

---

## ✨ Key Features

* 📂 **Multi-PDF Upload** — Supports simultaneous processing of multiple documents
* 🔎 **Intelligent Text Extraction** — Parses and cleans PDF content automatically
* 🧠 **Context-Aware Q&A** — Answers strictly based on document content
* 💬 **Conversational Interface** — Interactive chat powered by Google Gemini
* ⚡ **Fast Semantic Search** — Uses embeddings for accurate information retrieval
* 🖥️ **Clean UI** — Built with Streamlit for simplicity and responsiveness

---

## 🧠 Tech Stack

* **Frontend/UI:** Streamlit
* **LLM:** Google Gemini API
* **Orchestration:** LangChain
* **PDF Processing:** PyPDF2
* **Environment Management:** python-dotenv
* **Containerization:** Docker

---

## 📦 Getting Started

### 🔧 Prerequisites

* Python **3.10+**
* Google Gemini API Key
* (Optional) Docker

---

### 🐳 Run with Docker

1. Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key_here
```

2. Build and run the container:

```bash
docker compose up --build
```

3. Access the application in your browser:

```
http://localhost:8501
```

---

### 💻 Local Development Setup

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/HydraDocOc/gemini-pdf-chatbot.git
cd gemini-pdf-chatbot
```

#### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

#### 3️⃣ Configure Environment Variables

Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key_here
```

#### 4️⃣ Run the Application

```bash
streamlit run main.py
```

---

## 🧪 How to Use

1. Upload one or more PDF files using the sidebar
2. Click **Submit & Process** to extract and index document content
3. Ask questions in natural language
4. Receive answers grounded in the uploaded documents

---

## 📁 Project Structure

```
gemini-pdf-chatbot/
│
├── app.py              # Main Streamlit application
├── main.py             # Entry point
├── requirements.txt    # Python dependencies
├── .env                # Environment variables
└── README.md           # Project documentation
```

---

## 📚 Dependencies

* PyPDF2
* LangChain
* Streamlit
* google-generativeai
* python-dotenv

---

## 🎯 Use Cases

* Academic research assistance
* Legal & policy document analysis
* Technical documentation search
* Personal knowledge management
* Enterprise document Q&A systems

---

## 🙌 Acknowledgments

* Google Gemini — Large language model capabilities
* Streamlit — Rapid web app development framework
* LangChain — LLM application orchestration

---

## 👤 Author

**Dhawal Goyal**
# PaperIQ
