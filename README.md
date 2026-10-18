# Aurora-Stays-QnA

Aurora RAG: a retrieval-augmented question answering POC for AuroraStay Hotels staff.

- `backend/` Flask REST API (gunicorn, port 7860) serving a FAISS index built from the four hotel policy PDFs.
- `frontend/` Streamlit UI (port 8501) that calls the backend.

See the Dockerfiles in each folder; the backend expects `OPENAI_API_KEY` and `OPENAI_API_BASE` as environment variables (GitHub Codespaces secrets).
