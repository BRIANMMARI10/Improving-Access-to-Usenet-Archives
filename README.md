# Usenet Semantic Search and RAG Visualization Tool

This project builds an end-to-end semantic search engine and visualization tool over 20 Newsgroups data. It integrates FAISS for fast similarity search, UMAP for topic projection, and GPT-4o via AzureOpenAI for grounded RAG (Retrieval-Augmented Generation).


## Features

- **Semantic Search** across 18,000+ newsgroup posts using MiniLM embeddings and FAISS index.
- **2D Visualization** of topic clusters using UMAP and Plotly.
- **LLM-Powered Q&A**: Ask natural language questions and get grounded answers from GPT-4o.
- **Deployed Dash Interface**: Interactive, real-time exploration served with Ngrok.


## Project Structure

- `TRA301_Final_Colab.ipynb` – Full pipeline: embedding, FAISS, UMAP, RAG, Dash app  
- `TRA301_Report.pdf` – Final write-up documenting system design and evaluation  
- `demo_videos/` – Screen recordings of the deployed app  
- `README.md` – Project overview  


## Getting Started

### Prerequisites

- Python 3.10+
- GPU-enabled runtime recommended (e.g., Colab)
- Required packages:
  - `sentence-transformers`
  - `faiss-cpu`
  - `umap-learn`
  - `plotly`
  - `dash`
  - `pyngrok`
  - `openai`
  - `jupyter-dash`

### Installation

```bash
pip install sentence-transformers faiss-cpu umap-learn plotly dash pyngrok openai jupyter-dash
