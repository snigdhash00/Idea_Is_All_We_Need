📚 Idea is All We Need


🚀 Objective

This project builds an AI-powered tool to assist researchers in efficiently discovering, summarizing, and extracting insights from academic papers. It goes beyond basic retrieval by surfacing "Future Work" and "Limitations" sections, helping users explore research gaps and generate novel hypotheses.


🧠 Key Features

LLM-powered Summarization & QA
Semantic Search & Topic Modeling with Latent Dirichlet Allocation (LDA)
Section-specific Extraction (e.g., Future Work, Limitations)
CORE API Integration for full-text academic paper retrieval


📦 Dataset

Source: CORE Dataset
Format: JSON (structured with metadata + full text)
Includes: Title, Abstract, Sections (e.g., future work, conclusion)


🛠 Methodology

- Retrieve papers via CORE API
- Preprocess text using NLP pipelines
- Extract relevant sections (Future Work, Limitations)
- Embed & Search with BERT for semantic matching
- Summarize & Analyze using GPT-4 or custom QA modules
- Visualize insights via topic modeling (LDA)
