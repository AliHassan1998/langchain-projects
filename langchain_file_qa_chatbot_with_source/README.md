# LangChain File QA Chatbot

This Streamlit app allows users to upload PDFs, embed content using HuggingFace, store it in Qdrant, and chat with it using GPT-3.5 via LangChain.

## 🚀 Tech Stack
- LangChain
- OpenAI GPT-3.5
- HuggingFace Embeddings
- Qdrant Vector Store
- Streamlit UI
- PyPDF2 / DOCX for file reading

## 💡 Features
- Upload PDF files
- Generate embeddings
- Store in Qdrant
- Retrieve similar chunks
- Ask questions and get contextual answers

## 🛠 How to Run
```bash
pip install -r requirements.txt
streamlit run langchain_file_qa_chatbot.py
Create a .streamlit/secrets.toml with your API keys.
