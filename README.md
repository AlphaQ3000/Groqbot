# Docubot
Docubot is an AI chatbot designed to answer questions based on provided documents using Retrieval-Augmented Generation (RAG). It leverages the Groq API with the Llama3 model, LangChain for document processing, and Streamlit for the user interface.

FEATURES
Document Ingestion: Input and store multiple texts.
Text Splitting and Embedding: Efficiently split and embed text documents for retrieval.
Question Answering: Provide accurate answers based on the provided context.
Document Context Display: Display relevant document excerpts alongside the answers.
Requirements
Python 3.7+
Streamlit
LangChain
Groq API
FAISS
OllamaEmbeddings
Setup Instructions

1. Clone the Repository git clone 

2-Install Dependencies pip install -r requirements.txt

3-Set Up API Key Ensure you have a Groq API key. Set your Groq API key in the script: groq_api_key = "your_groq_api_key_here"

4-Run the Application streamlit run rag_bot.py

Usage Guide Enter the Document Use the text area to input the entire document you want the bot to use for answering questions. Click the "Save your document" button to process and save the document. Ask Questions Enter your question in the text input field. The bot will display the answer based on the provided context from the saved documents.

Project Structure groqbot.py: Main script containing the Streamlit app and logic for the RAG bot. requirements.txt: List of dependencies required for the project.

Contributing We welcome contributions to Text_Maven! If you have any improvements or suggestions, feel free to open an issue or submit a pull request.
