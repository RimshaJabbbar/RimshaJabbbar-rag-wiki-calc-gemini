# RimshaJabbbar-rag-wiki-calc-gemini
Smart AI Assistant built with Streamlit, FAISS, SentenceTransformers, Wikipedia, and Google Gemini API. Supports RAG for product knowledge, a calculator for math, and Wikipedia for general queries, with Gemini orchestrating responses.

Smart AI Assistant: Multi-Tool Answer Generator 🤖
This Streamlit app integrates multiple AI-powered tools into one assistant:

🔎 RAG System (FAISS + SentenceTransformers) → retrieves company-specific knowledge from uploaded text files (or sample GlobalMart docs).

➗ Calculator → evaluates safe math expressions.

🌍 Wikipedia Search → fetches concise world knowledge summaries.

🧠 Google Gemini (LLM) → acts as a planner and synthesizer to split queries, decide the best tool, and combine answers into a final human-like response.

Users can upload .txt files, query with multi-part questions (e.g., “What’s the return policy AND calculate 205; Who is Elon Musk?”*), and get structured answers.

⚙️ Tech Stack

Streamlit → interactive UI

FAISS → vector similarity search for RAG

SentenceTransformers (all-MiniLM-L6-v2) → embeddings

Wikipedia → general knowledge retrieval

Google Gemini API → reasoning, planning & response synthesis
