**DevHive**
**A Knowledge Transfer Platform for Technical Teams**

DevHive is a centralized and intelligent platform designed to streamline knowledge sharing within engineering teams. It enables users to store, organize, and retrieve technical documents, meeting notes, and GitHub activity using semantic search and AI-powered recommendations.

**Project Overview**
The platform addresses the common problem of scattered team knowledge across tools and formats. DevHive captures essential insights and makes them easily accessible through intelligent search and contextual assistance.

**Tech Stack**
Layer	Tools/Frameworks
Frontend	Streamlit (Python-based UI)
Backend	FastAPI (or Flask)
AI/LLM	Gemini API / OpenAI
Search/RAG	Vector Database (Pinecone or Qdrant), Redis
Storage/Cache	Redis
DevOps	GitHub for version control

**Features**
Semantic search using vector embeddings

AI-based summarization and recommendations

GitHub integration for syncing commits, PRs, and issues

Structured document upload and categorization

Fast and clean interface built with Streamlit

Redis caching for faster search and retrieval

**Setup Instructions**
1. Clone the repository

git clone https://github.com/your-org/devhive.git
cd devhive
2. Configure environment variables
Create a .env file in the project root:


VECTOR_DB_API_KEY=your_api_key
REDIS_URL=redis://localhost:6379
GEMINI_API_KEY=your_gemini_api_key
3. Run the application
If using Streamlit:


streamlit run app.py
If using FastAPI:

uvicorn main:app --reload

**License and Ownership**
This project is developed and maintained by the DevHive team as part of a hackathon initiative. For internal use only.

**Contribution & Support**
Found a bug or have a suggestion?
Feel free to open an issue or submit a pull request.
We welcome contributions from the community!
