### RAG - Retrieval Augmented Generation
*The RAG code performs the following tasks:*

    To summarize the overall flow:
    1.  Embeddings for question is generated.
    2.  Based on this embeddings the most similar content embedding is retrieved from vector DB (Pinecone)
    3.  Not this content and question is sent into the LLM model
    4.  parser gets the output and prints the string based on the context.


In order to execute the code, install requirements present in the first cell and have .env file which specifies the API keys for OPENAI and PINECONE,