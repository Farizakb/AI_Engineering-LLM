# LLM

Welcome to the **LLM** repository! This project is a comprehensive, hands-on journey through the evolution of Natural Language Processing (NLP) and modern Large Language Model (LLM) architectures. It covers everything from fundamental text processing techniques to advanced transformer concepts, Retrieval-Augmented Generation (RAG), and agentic workflows.

## 📚 Project Overview

In this project, I have worked on:
- **Foundational Deep Learning & Mathematics:** NumPy vectorization, logistic regression as a single-layer neural network, and shallow multi-layer neural networks from scratch.
- **Foundations of NLP:** Basic text processing, tokenization, and vectorization techniques.
- **Embeddings:** Traditional and modern ways to represent words and documents in vector space.
- **Transformer Architecture Deep Dive:** Positional encoding, attention mechanisms, and decoding strategies.
- **RAG & Agent Technologies:** Real-world applications of LLMs using LangChain, custom RAG systems, and AI agents.
- **Model Context Protocol (MCP):** Exploring advanced model context frameworks.

---

## 📂 Repository Structure & Topics

### 0. Foundational Deep Learning & Mathematics (`deep_learning_foundations`)
This section covers the core mathematical foundations, vectorization techniques, and early neural network architectures that power modern machine learning and large language models.
- **1-NumPy-Basics:** NumPy mathematics essentials for deep learning.
- **2-Logistic-Regression-NN-Mindset:** Binary image classifier (cat vs. non-cat) built with a neural network mindset.
- **3-Shallow-Neural-Networks:** 2-class planar data classifier with one hidden layer and non-linear activations.


### 1. NLP and Text Processing (`nlp_and_text_processing`)
This section covers the fundamental building blocks of Natural Language Processing.
- **1-Regex:** Pattern matching and text extraction.
- **2-Tokenization:** Splitting text into manageable tokens.
- **3-Text-Preprocessing:** Cleaning and standardizing text data.
- **4-BoW & N-grams:** Bag of Words and N-gram models for text representation.
- **5-TF-IDF & Word2Vec:** Term frequency-inverse document frequency and word embeddings.
- **6-Sentiment-Analysis:** Determining the sentiment or emotion of text.
- **7-POS & NER:** Part-of-Speech tagging and Named Entity Recognition.
- **8-RNN vs LSTM:** Exploring Recurrent Neural Networks and Long Short-Term Memory networks.
- **9-Advanced-NLP:** More complex NLP tasks and techniques.

### 2. LLM Embeddings (`llm_embedding`)
Understanding how words and sentences are represented as dense vectors.
- **1-CBOW-and-Skip-Gram:** Continuous Bag-of-Words and Skip-Gram models (Word2Vec).
- **2-SVD:** Singular Value Decomposition for dimensionality reduction.
- **3-GloVe:** Global Vectors for Word Representation.
- **4-FastText-n-gram:** Subword embedding models.
- **5-PCA-TSNE-visualization:** Visualizing high-dimensional embeddings in 2D/3D space.

### 3. Temperature and Positional Encoding (`llm_temprature_and_positional_encoding`)
Core concepts for controlling LLM output and injecting sequence order into transformers.
- **positional_encoding:** Basics of positional encodings.
- **positional_encoding_techniques:** Advanced positional encoding techniques.
- **temprature_top-k_top-p:** Decoding strategies (Temperature, Top-K, Top-P sampling) for controlling generation randomness and diversity.

### 4. Attention Mechanisms (`llm_attention`)
A deep dive into the heart of the Transformer architecture: Attention.
- **0-Basis-Q-K-V:** The fundamental concept of Queries, Keys, and Values.
- **1-Full-Attention:** Standard multi-head self-attention.
- **2-Sparse-Attention:** Techniques to reduce quadratic complexity.
- **3-Big-Birds-Attention:** BigBird's block sparse attention mechanism for long sequences.
- **4-Flash-Attention:** Hardware-aware, memory-efficient exact attention.
- **5-Multi-Head-Attention:** Implementing multi-head attention blocks.
- **6-Mixture-of-Experts:** MoE architectures for scaling model capacity.
- **7-End-to-end-Example-QnA:** Building a Question & Answering system using attention.
- **attention_visualization:** Tools and techniques to visualize attention weights.

### 5. RAG (Retrieval-Augmented Generation) (`llm_rag`)
Applying LLMs to external knowledge bases.
- **1-intro-and-chunking-strategies:** Introduction to RAG and optimal text chunking.
- **2-document-management:** Managing and indexing document vectors.
- **3-crm-automation:** Applying RAG for Customer Relationship Management.
- **4-document-answer-bot:** Creating a bot that answers questions based on documents.
- **5-finance-q-a-analysis:** Specialized Q&A for financial analysis.
- **6-healthcare-bot:** Healthcare-focused RAG implementation.
- **7-personalized-bot:** Customizing bots for individual users.
- **8-kaggle-rag-system:** Implementing a robust RAG system.

### 6. AI Workflows and Agents (`llm_ai_workflow`)
Orchestrating complex tasks using LLMs, tools, and chains (primarily using LangChain/LCEL).
- **1-LangChain-basic-prompt-chain:** Basics of prompting and chaining.
- **2-Pdf-rag-data:** Building RAG over PDF files.
- **3-Agent-tool-usage:** Enabling LLMs to use external tools.
- **4-Conversational-memory:** Implementing memory buffers for chatbots.
- **5-Conditional-sequential-chain:** Routing and sequential logic in chains.
- **6-Search-engine-and-python-repl:** Giving agents web search and code execution capabilities.
- **7-CSV-file-agent:** Querying and analyzing CSV data using LLM agents.
- **8-RAG-with-multiple-files:** Scaling RAG to handle multiple diverse documents.
- **9-Multi-tool-agent:** Creating advanced agents with multiple tool sets.
- **10-LCEL-rag-chain:** LangChain Expression Language (LCEL) for declarative pipelines.

### 7. Model Context Protocol (`llm_mcp`)
Exploration of MCP across various modules (`module-1` through `module-5`), enabling standardized interactions between models and structured environments.
