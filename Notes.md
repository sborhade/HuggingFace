RAG: Retrieval Augmented Generation

Data sources like files, audio, video.

Data ingestion: Getting or reading data from different data sources. 
Data transformation: tranform or divide data into chunks.
Embedding: example text embedding is converting the data into vectors
Store: we use data base like vector store databases like FAISS, ChromaDB, AtraDB to store the embedded data.

Then comes the phase of asking or running model on data.
AI assistant using LLM models will work on vector store data to generate response.

Document load chain: 
Retrieval chain: It is a interface to query vector store DB. based on this retrieval chain query we get the response.

