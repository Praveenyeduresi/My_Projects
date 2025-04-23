
## Project Title : Q&A System with Retrieval-Augmented Generation(RAG) Using Gemini.

**Technologies Used**: 
**Libraries**: LangChain, ChromaDB, NumPy, Pandas, PyPDFLoader---
**AI Models:** Google Generative AI (Gemini Pro, embedding-001)
**Languages**: Python.---
**Deployment**: Local (Notebook-based), Vector Store (ChromaDB).

**Overview**: To build a Retrieval-Augmented Generation (RAG) system that allows users to ask questions over research papers or technical documents, delivering accurate, context-aware responses by combining document retrieval with Google’s Gemini language model.

**The project follows several steps:**

**1. Data Preprocessing:** 
- Loaded multiple research papers using LangChain's PyPDFLoader.

- Combined all documents into a unified list for downstream chunking and embedding.

**2. Embedding & Indexing:**
- Applied embedding-001 from Google Generative AI to convert text chunks into vector embeddings.

- Stored embeddings in ChromaDB, a persistent vector database.

- Enabled fast and scalable similarity search across documents.

**3. Retrieval-Augmented Generation (RAG) Pipeline:**
- User query is embedded and matched to relevant document chunks using cosine similarity.

- Retrieved chunks are fed into Gemini Pro via LangChain’s prompt templating.

- Gemini Pro generates an intelligent, context-aware response based on the retrieved content.

**4. System Design & Testing:**
- Modular pipeline created with LangChain for clean retriever-LLM interaction.

- Multiple queries were tested manually to evaluate response quality and relevance.

- Integrated prompt engineering to optimize Gemini’s use of retrieved context.

**Manual Testing**

**Conclusion**: 
This RAG system effectively bridges the gap between unstructured documents and intelligent querying. By combining semantic retrieval with Google’s Gemini model, it enables users to extract meaningful insights from large document collections. The modular design supports future scalability, multi-document input, and domain-specific applications like legal, research, or medical document Q&A.

