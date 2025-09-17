# 📄 Chat with Documents (PDF Q&A Bot)

An **AI-powered PDF Question Answering Bot** built with **Hugging Face Transformers**.  
This project lets you upload a PDF document and ask questions about its content.  
The bot will answer *only* based on the document text — no external knowledge is used.

---

##  Features
-  Extracts text from PDF files
-  Uses open-source Hugging Face LLMs for question answering
-  Handles long documents with a maximum context size (`MAX_CONTEXT_CHAR = 6000`)
-  Answers strictly from the document 
