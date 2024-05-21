ChatWithYourPDF_Bot

ChatWithYourPDF_Bot is an interactive chatbot designed to help users upload PDF documents and interact with their content through conversational queries. Built using LangChain, OpenAI's GPT-3.5-turbo model, and Panel for the dashboard interface, this chatbot allows users to ask questions regarding their documents and receive contextually relevant answers. This project can be especially useful for educational purposes, research, and any scenario requiring efficient information retrieval from documents.

Features
PDF Document Upload: Users can upload their PDF documents to the chatbot.
Conversational Interaction: The chatbot uses OpenAI's GPT-3.5-turbo model to answer questions based on the content of the uploaded PDF.
Contextual Memory: The chatbot maintains conversation context for more coherent and relevant responses.
Document Embedding and Retrieval: The project leverages OpenAI embeddings to create a vector store for efficient document retrieval.
Interactive Dashboard: Built with Panel, the dashboard provides a user-friendly interface for uploading documents, chatting, and viewing query history.

Technical Details
Dependencies
LangChain: For document processing, embeddings, and conversational AI chains.
OpenAI: Utilizes the GPT-3.5-turbo model for natural language processing.
PyPDF: For loading and processing PDF documents.
DocArray: For creating and managing the in-memory vector store.
Panel: For creating the interactive dashboard.

Usage
Loading a Document
Users can load a PDF document using the file input widget and the "Load DB" button. The document is processed and split into chunks for efficient querying.

Asking Questions
Users can input their questions in the text input field. The chatbot processes the query, retrieves relevant information from the document, and responds with a contextually appropriate answer.

Viewing Query History
The dashboard includes tabs to view the last database query, source documents, and the entire chat history, providing transparency and traceability of the interaction.
