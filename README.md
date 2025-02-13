# Efficiently Searching PDF Content with Ollama AI: Leveraging LLMs and RAG for Enhanced Retrieval

This sample demonstrates how to **ingest** text from **PDF** files into a **vector store**

Also ask questions about the content using an **LLM(Large Language Model)** while using **RAG(Retrieval Augment Generate)** to supplement the LLM with additional information from the vector store

![image](https://github.com/user-attachments/assets/0b17e275-2d3d-4a52-a287-5781d7542c85)

In short, this code sets up a **Hosted Service** within a .NET Core application, suitable for a **background application** or API server that needs to **run continuously** and manage external service dependencies

A **Console Application**, on the other hand, is more suited to simpler, finite tasks that don’t require such extensive dependency management or runtime control

## 1. Application architecture

The application is integrated by this main components:

1. ChatCompletion Service ()

2. Embedding Service (for translating the PDF content into Vectors for storing them in a VectorDataBase)

3. Vectors Store Type (in this case InMemory)

4. PDFs docs stored in localhost or in other cloud server (Azure Blobs, AWS S3, etc) or in a DataBase (Azure SQL, etc) 

## 2. How to run the application 

Create an API Key in OpenAI for the Embeddings Service

https://platform.openai.com/settings/organization/api-keys

Select the ChatCompletion (Ollama) and EmbeddingService (OpenAI) in the configuration file

**appsettings.json**

```json

```





