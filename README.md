# RAG_Effectiveness

To analyse the effectiveness of RAG, we started with implementing a RAG pipeline. Since Ollama offers access to multiple LLMs models and offeres also embedding function, it was more effecient to use it for local model hosting especially that we wanted to test effeciency of RAG with different models. We used embedding function, model ("nomic-embed-text"). Two LLMs were used: "Llama3" and "Qwen 1.8".

### Steps:
1. Create a local DB.
2. Choose a path and load context of dataset.
3. Using embedding function from ollama, embedd the chunks and add them to our DB.
4. Set LLM, using model specified through Ollama.
5. Either query with context, or without context.


