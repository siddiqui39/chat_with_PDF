
# Chat with PDF

This repository includes all the code and resources for a project that enables you to chat with PDF documents through an interactive graphical interface. The project is built entirely using Python and leverages LangChain to process and understand the content of PDFs, making it easy to upload documents, ask questions, and receive AI-generated answers directly from your files.


## How does it work
The application processes PDF files by extracting and splitting the text into smaller chunks, which can then be used by a language model. It leverages OpenAI embeddings to convert these chunks into vector representations. When a user asks a question, the app identifies the chunks that are most semantically relevant and provides them to the language model to generate an accurate response.

The graphical interface is built with Streamlit, while LangChain handles the interactions with the language model, making the workflow seamless and efficient.
## Requirements

 1. Python 3.10 or higher
 2. streamlit – for creating the graphical user interface
 3. PyPDF2 – for reading and extracting text from PDF files
 4. langchain – for handling text splitting, embeddings, vector stores, and QA chains
 5. FAISS – for storing and searching vector embeddings
 6. OpenAI API key

  
