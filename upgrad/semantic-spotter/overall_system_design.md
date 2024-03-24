# System Design of Semantic Spotter

High level system design is given below:
[System Design](./system_design.png)

To resolve this problem Complete approach is divided into 4 parts:

1. **Chunking** Process knowledgw base and break each documnet into small chunks

2. **Embedding and Store in Vector DB** Split chunks and store them into vector database

3. **Similarity Search** User send a query to vector db, and get relevant context from vector db

4. **Generative Search** Use LLM to generate response of user query. As an input we are passing user query and relevant context. LLM will genrate a nice representative response.

