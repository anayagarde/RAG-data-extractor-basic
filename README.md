## RAG PDF Data Extractor 

Created a basic pdf data extractor app using RAG (Retrieval Augmented Generator). 
1. Load PDFs using LangChain's PyPDFDirectoryLoader method
2. Split the documents in small chunks using LangChain's RecursiveCharacterTextSplitter method
3. Create vector embeddings for each chunk using HuggingFaceEmbeddings
4. Add vector embeddings to vector store database - Chroma
5. Retrieving top k most relevant documents from Chroma based on user's query/prompt
6. Generate Response using google/flan-t5-base LLM model

<img width="412" alt="image" src="https://github.com/user-attachments/assets/c3f38adf-3665-422e-978c-9d8f94dc1c34" />

