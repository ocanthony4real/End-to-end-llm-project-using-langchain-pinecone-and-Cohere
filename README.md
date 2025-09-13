## 📘 PDF Question Answering Chatbot

This project is an AI-powered chatbot that can read, understand, and answer questions from your PDF documents. It combines LangChain, Cohere embeddings & LLMs, and Pinecone vector database to provide intelligent document retrieval and conversational Q&A.

## 🚀 Features
-Load and process multiple PDF documents.  
-Split large documents into smaller, overlapping text chunks for better context retrieval.  
-Store and query embeddings in Pinecone  
-Ask natural language questions and get answers directly from your documents  
-Powered by LangChain + Cohere  

## 🛠️ Tech Stack
-LangChain: framework  
-Cohere: Embeddings + LLM  
-Pinecone: Vector database  
-Python: programming language  

## ⚙️ Installation (using Git Bash)   
1. Clone this repository:  
```bash
git clone https://github.com/ocanthony4real/End-to-end-llm-project-using-langchain-pinecone-and-Cohere
cd End-to-end-llm-project-using-langchain-pinecone-and-Cohere
```

2. Create a virtual environment and install dependencies:
```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Edit your ```.env``` file with API keys:
```
COHERE_API_KEY=your_cohere_key
PINECONE_API_KEY=your_pinecone_key
```

## Procedure to run file  
1. Create a ```documents/``` folder and insert a PDF file  
2. Open and run the ```main.ipynb``` file
3. Edit the query in the script to reflect the context of the uploaded PDF
