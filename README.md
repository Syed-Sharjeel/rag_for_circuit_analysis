# rag_for_circuit_analysis
A GenAI-powered RAG assistant built on Fundamentals of Electric Circuits for answering textbook-based questions using embeddings, ChromaDB, and Gemini API.
# ElectricCircuitRAG — GenAI-Powered Textbook Assistant

ElectricCircuitRAG is a Retrieval-Augmented Generation (RAG) assistant powered by Google's Gemini API. It answers questions based on the *Fundamentals of Electric Circuits* textbook by Charles K. Alexander and Matthew N. O. Sadiku. Built as part of the **Google x Kaggle GenAI Intensive Capstone 2025Q1**, it showcases semantic search, document understanding, and structured response generation.

---

## Features

- Chapter-wise text chunking and metadata tagging
- Embeddings via `models/text-embedding-004`
- Vector storage with ChromaDB
- Semantic search and document retrieval
- Structured JSON outputs
- Chapter summaries via function calling

---

## Tech Stack

- Google Gemini API (Pro + Embeddings)
- ChromaDB
- Python 3.11+
- PyMuPDF (for PDF parsing, optional)
- Jupyter Notebook

---

## How It Works
1. **Clean & Chunk:** Preprocess the textbook and chunk it by chapter
2. **Embed:** Convert each chunk into embeddings using Gemini
3. **Store:** Save them with metadata in ChromaDB
4. **Query:** Use user questions to retrieve similar chunks
5. **Generate:** Prompt Gemini to answer using only the retrieved content

---

## Capabilities Demonstrated
- Embeddings
- RAG (Retrieval-Augmented Generation)
- Vector Search & Metadata Filtering
- JSON Output (Controlled Generation)
- Function Calling for Summaries

---

## Future Enhancements
- UI with Streamlit or Gradio
- Multi-turn memory & context caching
- Expand to multiple textbooks
- Integrate with Google Cloud Vertex AI

---

## License
This project is for educational purposes under the GenAI Intensive Course. All rights reserved for the textbook content.
