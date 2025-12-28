# semantic_document_search_gen-ai

Semantic search allows computers to understand the meaning behind user queries rather than relying only on exact keyword matching. Using FAISS (Facebook AI Similarity Search), we can build a high-performance system that searches through hundreds or even thousands of documents by meaning and not just by text overlap. This approach enables smarter, faster, and more context-aware information retrieval.

## Working

Step 1: Document Ingestion  
PDF, DOCX, and TXT files are read and converted into text.

Step 2: Chunking  
Each document is split into smaller, meaningful parts.

Step 3: Embedding Generation  
Text chunks are converted into dense vector representations.

Step 4: FAISS Indexing  
Embeddings are stored in FAISS for efficient similarity search.

Step 5: Query Encoding  
A user query is embedded into the same vector space.

Step 6: Similarity Search  
FAISS finds top matches based on cosine similarity.

Step 7: Results Display  
The most relevant document snippets are shown.

## Tech Stack

- Programming Language: Python  
- Embedding Model: Sentence Transformers
- Vector Database: FAISS  
- Libraries: NumPy, PyMuPDF, python-docx, PyPDF2  


