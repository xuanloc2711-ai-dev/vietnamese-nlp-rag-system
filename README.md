# Title: Vietnamese NLP RAG System

# Project Overview
This project implements a Vietnamese Document Intelligence System that combines
traditional NLP techniques, Machine Learning, Deep Learning, and a Retrieval-Augmented
Generation (RAG) pipeline to perform document classification, semantic search, and
document-grounded question answering.

# Key features
- Vietnamese text preprocessing and tokenization
- Text classification using traditional ML and Deep Learning models
- Semantic document retrieval using vector embeddings
- RAG-based question answering grounded on retrieved documents

# Tech Stack
- Python
- Scikit-learn
- PyTorch
- Sentence Transformers
- FAISS
- FastAPI

# Project Structure
src/
- data_loader/      # Dataset loading and preprocessing pipeline
- preprocessing/    # Vietnamese text cleaning and tokenization
- models/           # ML and DL models for text classification
- retrieval/        # TF-IDF and vector-based document retrieval
- rag/              # RAG pipeline (retrieval + generation)
- evaluation/       # Model evaluation utilities

# Roadmap
- Phase 1: Data collection, preprocessing, and EDA
- Phase 2: Text classification with ML models
- Phase 3: Deep Learning-based text classification
- Phase 4: Semantic search and Retrieval-Augmented Generation (RAG)
