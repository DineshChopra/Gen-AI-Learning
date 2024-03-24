## Project Goal: [reference](./problem_statement.md)

## Data Source [Reference](/content/drive/MyDrive/Gen AI Course/RAG_For_HDFC_Policy/data)

## Design Choice
We choose LangChain, because this is used in industry and its very popular and powreful framework.

## Challenged Faced: NA

## Flow Chart:

![Flow Chart](./system_design.png)

## Problem Solution step by step approach

1. Load pdf files and break them into pages
![Step 1](./images/Step%201%20Chunking%20Break%20pdf%20into%20pages.png)

2. Load pages into chunks and store them in vector db (chromadb)
![Step 2](./images/Step%202%20Split%20pages%20into%20chunks%20and%20store%20it%20into%20vector%20do.png)

3. Similarity Search
![Step 3](./images/Step%203%20Similarity%20Search.png)

4. Generative Search
![Step 4](./images/Step%204%20Generative%20Search.png)

5. User Query response
![User query response](./images/response.png)



[Problem Statement](./problem_statement.md)

[Overall System Design](./overall_system_design.md)

[Code Implementation](./RAG_with_LangChain.ipynb)

