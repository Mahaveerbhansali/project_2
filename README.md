Aircraft Maintenance Manual Chatbot
The goal of this project is to create an interactive chatbot that can respond to queries using a PDF version of an airplane maintenance handbook. By employing Natural Language Processing (NLP) methods such as question-answering models and embedding-based search, the chatbot finds pertinent material in the manual and responds to user inquiries.

Features
PDF parsing is the process of automatically extracting text from an uploaded PDF aviation maintenance handbook.
Embedding-Based Search: Encodes text passages using a SentenceTransformer model and stores them in an FAISS vector index for effective similarity searching.
Question-Answering: Utilizes the "question-answering" pipeline developed by Hugging Face to respond to user inquiries by drawing on pertinent context from inside the document.
Ask questions using the user-friendly interface of an interactive chatbot, and get responses based on the airplane handbook.
