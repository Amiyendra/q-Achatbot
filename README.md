# q-Achatbot
# Conversational RAG with PDF Uploads and Chat History

This project is a **Conversational Retrieval-Augmented Generation (RAG)** application built using **LangChain**, **Groq**, and **Streamlit**. It allows users to upload PDF documents, extract their content, and interact with the extracted knowledge via a conversational interface. The application also maintains chat history for a more context-aware experience.

---

## Features
- **PDF Upload**: Upload a PDF document to extract and query its content.
- **Conversational AI**: Chat with the document content using Groq's large language models.
- **Contextualized Responses**: The app leverages chat history for more context-aware and relevant answers.
- **Retrieval-Augmented Generation (RAG)**: Combines document embeddings and a generative AI model for precise and informed responses.
- **Chat History Management**: Each session maintains a history of messages for a seamless conversation.

---

## Requirements
### Python Libraries
- **Streamlit**: For building the web interface.
- **LangChain**: For retrieval and chain management.
- **LangChain Community Extensions**: For advanced vector store and PDF loading capabilities.
- **HuggingFace**: For generating embeddings from text.
- **PyPDFLoader**: For extracting text from PDF documents.
- **Chroma**: For storing and retrieving document embeddings.
- **dotenv**: To load environment variables for API keys.

### API Keys
1. **Groq API Key**: Required to access Groq's large language models.
2. **HuggingFace Token**: Required for embedding generation.

Ensure these keys are stored securely in a `.env` file.

---

## Setup and Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
