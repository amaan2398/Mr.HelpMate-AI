# Mr.HelpMate-AI
## Retrieval-Augmented Generation (RAG) System for Policy Documents
### Project Overview
This project is a sophisticated question-answering system designed to provide accurate, grounded responses based on a specific set of policy documents. It uses a Retrieval-Augmented Generation (RAG) architecture to combine the power of a large language model (LLM) with a custom knowledge base, ensuring that all answers are factual and directly traceable to the source material.
### Features
- Document Ingestion: Efficiently loads and processes PDF documents from a specified directory.
- Intelligent Chunking: Splits documents into semantically meaningful chunks to optimize retrieval.
- Semantic Search: Utilizes vector embeddings and a FAISS vector store for fast and accurate similarity searches.
- Contextual Q&A: Grounds a gemini-1.5-flash LLM with retrieved context to generate precise and relevant answers.
- Secure API Handling: Uses environment variables to securely manage sensitive API keys.

### Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.x
- pip (Python package installer)

### Setup and Installation
Install Required Libraries:
The project relies on several key libraries. Run the following commands to install them:

```
pip install -U langchain-community pypdf faiss-cpu langchain-google-genai
```
### File Structure
Policy_Docs/: A directory where you place your PDF policy documents.
