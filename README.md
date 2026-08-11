# 🧠 PersonalGPT

**PersonalGPT** is a privacy-focused, AI-powered document assistant that allows users to chat with their personal documents using Large Language Models (LLMs). It leverages **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware responses while ensuring complete control over user data.

---

## 🚀 Features

- 🔒 **Privacy-First Architecture** – Keep your documents secure with local processing.
- 📄 **Multi-Document Support** – Upload and query PDFs, DOCX, TXT, Markdown, HTML, CSV, PPTX, and more.
- 🤖 **LLM Powered** – Integrates with local and cloud-based Large Language Models.
- 🔍 **Semantic Search** – Finds relevant information based on meaning, not just keywords.
- 🧠 **Retrieval-Augmented Generation (RAG)** – Generates accurate answers using document context.
- ⚡ **Real-Time Responses** – Fast and interactive AI conversations.
- 📦 **Vector Database Integration** – Efficient document retrieval using vector embeddings.
- 🌐 **REST API Support** – Easy integration with external applications.
- 🛠️ **Modular Architecture** – Easily extend or customize each component.
- 💻 **Cross-Platform Support** – Runs on Windows, Linux, and macOS.

---

## 🏗️ System Architecture

```text
                +------------------+
                |   User Uploads   |
                |     Documents    |
                +---------+--------+
                          |
                          v
                +------------------+
                | Document Parsing |
                +---------+--------+
                          |
                          v
                +------------------+
                | Embedding Model  |
                +---------+--------+
                          |
                          v
                +------------------+
                | Vector Database  |
                +---------+--------+
                          |
            User Query    |
                |         |
                v         |
        +-----------------------+
        | Semantic Retrieval    |
        +-----------+-----------+
                    |
                    v
          +----------------------+
          | Large Language Model |
          +-----------+----------+
                      |
                      v
             AI Generated Answer
```

---

## 📂 Project Structure

```text
PersonalGPT/
│
├── app/                    # Backend source code
├── frontend/               # Web interface
├── data/                   # Uploaded documents
├── models/                 # LLM & embedding models
├── vectorstore/            # Vector database
├── api/                    # REST APIs
├── config/                 # Configuration files
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🛠️ Tech Stack

### Backend
- Python
- FastAPI
- LangChain
- Hugging Face Transformers

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### AI & Machine Learning
- Llama 3 / Mistral / Gemma
- Sentence Transformers
- Retrieval-Augmented Generation (RAG)

### Vector Database
- ChromaDB
- FAISS
- Qdrant

### Database
- SQLite
- PostgreSQL (Optional)

---

## 📑 Supported File Formats

- PDF
- DOCX
- TXT
- Markdown
- HTML
- CSV
- PPTX
- EPUB

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/PersonalGPT.git
cd PersonalGPT
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate it

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

or

```bash
uvicorn app:app --reload
```

---

## 📌 Workflow

1. Upload your documents.
2. Documents are parsed and converted into embeddings.
3. Embeddings are stored in a vector database.
4. User enters a question.
5. Relevant document chunks are retrieved.
6. Context is sent to the LLM.
7. AI generates an accurate answer based on the retrieved context.

---

## 🎯 Applications

- 📚 Personal Knowledge Management
- 📑 Research Paper Assistant
- 🏥 Healthcare Document Analysis
- ⚖️ Legal Document Assistant
- 💼 Enterprise Knowledge Base
- 📊 Financial Report Analysis
- 🎓 Educational Learning Assistant
- 🤖 Personal AI Chatbot

---

## 🔮 Future Enhancements

- Voice-based interaction
- OCR support for scanned documents
- Multi-user authentication
- Cloud deployment
- Mobile application
- AI agents and workflow automation
- Multilingual document support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/NewFeature
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to the branch

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Shriram Kulkarni**

- 💼 AI & Data Science Engineer
- 🌐 Passionate about Generative AI, RAG, LLMs, and Full-Stack Development

---

⭐ If you found this project useful, don't forget to **Star** the repository!
