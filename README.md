 AI-Powered Research Assistant Agent

An agentic AI project for researchers that lets you:
-  Search papers by topic (arXiv API)
-  Upload and summarize PDFs
-  Chat with PDFs (semantic search + Q&A)
-  Compare multiple papers & extract citations
-  Generate reports and visualizations

Built with Hugging Face, SentenceTransformers, FAISS, and Gradio.  
Runs on Google Colab or locally.


Features & Phases
1. Phase 1 - Topic search + PDF summarization ✅  
2. Phase 2 - Q&A chatbot for PDFs (RAG)  
3. Phase 3 - Multi-paper comparison + citation extraction  
4. Phase 4 - Frontend download + visualization features  

agents      - summarizer, Q&A, comparison logic
utils       - arXiv search, PDF parsing, embeddings
ui       - Gradio interface
