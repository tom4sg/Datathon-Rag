# Corner Datathon: Vibe-based Search Recommendation System

This project implements a **hybrid semantic search engine** for places using a combination of:
- **Dense embeddings** (MiniLM / SentenceTransformer)
- **Sparse embeddings** (e.g., SPLADE via FastEmbed)
- **Image embeddings** (CLIP ViT-B/32)

The goal is to enable more effective retrieval and discovery of places based on metadata, reviews, and image content, blending structured and unstructured signals.

---

## Features
- Combines **dense, sparse, and image-based embeddings** for robust similarity search
- Uses **FAISS** for efficient nearest neighbor search on dense/image vectors
- Supports **cosine similarity** search for sparse embeddings
- Implements **weighted hybrid scoring** with configurable weighting
- Batching, normalization, and pooling strategies for scalability

---
