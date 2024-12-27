# RAG_Effectiveness

To analyse the effectiveness of RAG, we started with implementing a RAG pipeline. Since Ollama offers access to multiple LLMs models and offeres also embedding function, it was more effecient to use it for local model hosting especially that we wanted to test effeciency of RAG with different models. We used embedding function, model ("nomic-embed-text"). Two LLMs were used: "Llama3" and "".

### Steps:
1. Create a local DB.
2. Choose a path and load documents (pdf).
3. Documents were splitted into chunks
4. Using embedding function from ollama, embedd the chunks and add them to our DB.
5. Set LLM, using model specified through Ollama.
6. Either query with context, or without context.

### Next steps include:
* choose another model.
* compare answers with specified metrics.
