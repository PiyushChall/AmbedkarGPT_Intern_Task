# AmbedkarGPT_Intern_Task
A Retrieval Augmented Generation project that uses LangChain, ChromaDB, HuggingFace embeddings and Ollama Mistral 7B to build a local QnA system and a complete RAG evaluation engine.

📖 Overview

This repository contains the full solution for the Kalpit Pvt Ltd . UK . AI Intern Hiring Assignment.
It is divided into two major parts.

Assignment 1. Build a functional RAG prototype
Assignment 2. Build a complete evaluation framework for multiple documents

All components are fully local . no API keys, no paid services.

📌 Project Phases
Phase 1. Functional RAG Prototype

Will build a complete QnA system using
• LangChain
• ChromaDB
• HuggingFaceEmbeddings. all-MiniLM-L6-v2
• Ollama with Mistral 7B

This phase outputs a command line application that can answer questions using only the provided speech.txt content.

Phase 2. Evaluation Framework Setup

Will set up evaluation.py to
• load the corpus documents,
• load the test dataset with 25 QnA pairs,
• generate three chunking strategies and
• evaluate retrieval results.

Phase 3. Advanced Metrics and Comparative Analysis

Will implement
• Hit Rate
• MRR
• Precision at K
• Answer Relevance
• Faithfulness
• ROUGE-L
• Cosine Similarity
• BLEU

We will test small . medium . large chunk sizes and store results in test_results.json.

Phase 4. Final Analysis and Recommendations

Will produce a full analytical report in results_analysis.md which describes
• best performing chunk size,
• overall accuracy,
• major failure patterns,
• recommended improvements.

📌 Tech Stack

• Python 3.8+
• LangChain
• ChromaDB
• HuggingFace sentence-transformers
• Ollama (Mistral 7B)
• ragas, rouge-score, nltk, sklearn for metrics

Everything runs locally and offline.

🚀 How to Run
Install dependencies
pip install -r requirements.txt

Start Ollama server
ollama serve
ollama pull mistral

Run the RAG QnA System
python src/main.py

Run Evaluation
python src/evaluation.py

📌 Output of This Project

By the end of this repository, you will have
• A fully functional local RAG system
• A complete evaluation and metrics pipeline
• A chunking comparison study
• A detailed performance analysis
• Production-ready and clean codebase
