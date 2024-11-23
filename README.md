# LocalDoc
Personal - Private LLM

It addresses the inherent privacy concerns associated with online cloud based LLM chatbots by providing a high performance local solution for handling private documents.

- Developed a personalized, secure, and offline RAG (Retrieval-augmented generation) model.
- Enables users to upload personal documents and inquire about them while ensuring privacy by operating locally.
- Langchain framework is used.
- Sentence Transformers model is used for creating embeddings and ChromaDB vector database for storage.
- Mistral 7b instruct LLM model is chosen for its superior performance over Llama2 in various benchmarks.
- Hosted the project using Streamlit for seamless interaction and accessibility.

When a user submits a query, LocalDoc performs a similarity search within the vector database. It retrieves relevant document chunks, generates an output, and provides context to both the documents and the user input, ensuring a comprehensive understanding of the information retrieved.

<img src="Web%20app/Web-UI.png">

Team Details:
- Ayam Bhura
- Piyush Sahoo
