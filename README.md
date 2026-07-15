# RAG From Scratch

A simple Retrieval-Augmented Generation (RAG) project built from scratch to understand how modern AI applications retrieve relevant information before generating responses.

## Why I Built This

I wanted to understand how RAG systems work internally instead of relying only on frameworks. This project helped me learn the complete pipeline, from loading documents to retrieving relevant context and generating answers using an LLM.

## Features

- Load PDF documents
- Split documents into smaller chunks
- Generate vector embeddings
- Store embeddings in a FAISS vector database
- Retrieve relevant chunks using similarity search
- Generate answers using Google Gemini
- Simple Streamlit interface

## Tech Stack

- Python
- LangChain
- Google Gemini
- FAISS
- Streamlit
- PyPDF
- Sentence Transformers

## Project Structure

```text
rag-from-scratch/
│
├── src/
├── data/
├── docs/
├── screenshots/
├── tests/
└── notebooks/
```

## Getting Started

Clone the repository.

```bash
git clone https://github.com/YOUR_USERNAME/rag-from-scratch.git
cd rag-from-scratch
```

Install the required packages.

```bash
pip install -r requirements.txt
```

Create a `.env` file.

```env
GOOGLE_API_KEY=your_api-key
```

Run the application.

```bash
streamlit run src/app.py
```

## What I Learned

While building this project, I learned:

- How text is converted into embeddings
- How vector databases like FAISS perform similarity search
- How retrieval improves LLM responses
- How to connect LangChain components into a complete RAG pipeline
- How to organize a Python project with a clean structure

## Future Improvements

- Support multiple PDF documents
- Add hybrid search (BM25 + Vector Search)
- Improve prompt engineering
- Add chat history
- Dockerize the application

## License

MIT License
## 📄 License

This project is licensed under the MIT License.
