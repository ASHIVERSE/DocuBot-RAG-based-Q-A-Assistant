# DocuBot-RAG-based-Q-A-Assistant
An intelligent AI-powered Document Question & Answer system that allows users to upload a PDF (notes, PPT exports, documents) and ask questions in natural language.

The system retrieves relevant content from the document and generates clear, user-friendly answers in either:

Bullet points, or
Short explanatory paragraphs
based on the intent of the question.

🚀 Features
📄 Upload PDF documents
🔍 Semantic search using vector embeddings (FAISS)
🧠 Retrieval-Augmented Generation (RAG)
✍️ Clean, summarized answers (no prompt leakage)
🧾 Bullet-point or paragraph answers based on question type
❌ Graceful fallback if the answer is not found
🌐 Deployed using Streamlit Cloud
🛠️ Tech Stack
Python 3.10
Streamlit – Web interface
LangChain – RAG pipeline
FAISS – Vector similarity search
Sentence-Transformers – Local embeddings
facebook/bart-large-cnn – Text summarization model
HuggingFace Transformers
🧠 How It Works (RAG Flow)
PDF is uploaded by the user
Text is extracted and split into chunks
Chunks are converted into vector embeddings
FAISS retrieves the most relevant chunks
The LLM summarizes content based on the question
Output is formatted cleanly for the user
