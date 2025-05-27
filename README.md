## RAG PDF Data Extractor 

Created a basic pdf data extractor app using RAG (Retrieval Augmented Generator). 
1. Load PDFs using LangChain's PyPDFDirectoryLoader method
2. Split the documents in small chunks using LangChain's RecursiveCharacterTextSplitter method
3. Create vector embeddings for each chunk using HuggingFaceEmbeddings
4. Add vector embeddings to vector store database - Chroma
5. Retrieving top k most relevant documents from Chroma based on user's query/prompt
6. Generate Response using google/flan-t5-base LLM model
