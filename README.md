# ML-FinanceTheory
Machine Learning in Finance has been shaping the market for years now. A lot of the attention is given to formulas and analysis. However, a very little attention is given to Theory. For this project, we shed light on the theory part.

# FinanceRAG: A Machine Learning Q&A System for Finance

FinanceRAG is a Retrieval-Augmented Generation (RAG) system that answers complex questions from the field of Machine Learning in Finance. It uses the book *Machine Learning for Asset Managers* by Marcos López de Prado as its core knowledge base.

Built with:
-  Sentence-Transformer Embeddings
-  Chroma Vector Database
-  Falcon-RW-1B (or any Hugging Face-compatible LLM)
-  LangChain pipeline

---

##  Objective

To create a smart, local Q&A system that helps users:
- Understand ML concepts in finance
- Explore theories, use cases, and tools covered in López de Prado’s work
- Avoid overfitting, backtest pitfalls, and misuse of statistics in asset management

---

##  Features

-  Load and chunk entire financial books or PDFs
-  Semantic search using vector similarity
-  Answers questions using a Hugging Face LLM
-  Easily swappable models (Mistral, Falcon, GPT2, etc.)
-  Fast and local — no cloud APIs required!

---

## Things used:
- model_name = "tiiuae/falcon-rw-1b"
- A HuggingFace token (API key)



