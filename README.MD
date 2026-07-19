# 🤖 GenAI Research Assistant

An AI-powered Research Assistant that helps users analyze, summarize, and interact with research papers using Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and semantic search.

The application allows users to upload research papers, ask contextual questions, generate concise summaries, and retrieve relevant information instantly through natural language conversations.

---

## 🚀 Features

- 📄 Upload research papers in PDF format
- 🧠 AI-powered document summarization
- 💬 Chat with your research papers
- 🔍 Semantic search using embeddings
- 📚 Retrieval-Augmented Generation (RAG)
- ⚡ Fast response generation with LLMs
- 📝 Context-aware question answering
- 🔒 Secure API key management using environment variables

---

## 🏗️ Tech Stack

### Frontend
- Streamlit / Gradio *(Replace with your frontend)*

### Backend
- Python
- LangChain
- FastAPI *(if applicable)*

### AI Models
- Google Gemini
- OpenAI GPT
- HuggingFace Models *(Replace with your model)*

### Vector Database
- ChromaDB
- FAISS *(Replace with your DB)*

### Embeddings
- Google Embeddings
- OpenAI Embeddings
- HuggingFace Embeddings

---

## 📂 Project Structure

```
GenAI-Research-Assistant/
│
├── app.py
├── requirements.txt
├── README.md
├── .env
│
├── data/
│   ├── uploaded_pdfs/
│   └── vector_store/
│
├── utils/
│   ├── pdf_loader.py
│   ├── embeddings.py
│   ├── rag_pipeline.py
│   └── helpers.py
│
├── templates/
└── assets/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/GenAi-Research-Assistant.git

cd GenAi-Research-Assistant
```

Create a virtual environment

```bash
python -m venv venv
```

Activate it

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

Example:

```env
GOOGLE_API_KEY=your_google_api_key

OPENAI_API_KEY=your_openai_api_key
```

Only include the API key(s) required by your project.

---

## ▶️ Running the Project

If using Streamlit

```bash
streamlit run app.py
```

If using FastAPI

```bash
uvicorn app:app --reload
```

---

## 💡 How It Works

1. Upload a research paper (PDF).
2. Extract text from the document.
3. Split text into chunks.
4. Generate embeddings.
5. Store embeddings inside the vector database.
6. Retrieve relevant chunks using semantic search.
7. Pass retrieved context to the LLM.
8. Generate an accurate answer with citations/context.

---

## 📸 Demo

Add screenshots or GIFs here.

```
assets/demo.gif

assets/homepage.png
```

---

## 📦 Dependencies

Some major libraries used:

- LangChain
- Google Generative AI
- OpenAI
- ChromaDB
- FAISS
- PyPDF
- Streamlit
- python-dotenv

---

## 🎯 Future Improvements

- Multi-document chat
- Research paper comparison
- Citation generation
- Export answers to PDF
- Voice interaction
- OCR support for scanned PDFs
- User authentication
- Cloud deployment

---

## 🤝 Contributing

Contributions are always welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Ronit**

GitHub: https://github.com/ronit-codes12

