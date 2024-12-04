# Microsoft Fabric Databases - Back From Ignite 2024

This GitHub repository is linked to **Azure-Samples/fabric-rag-langchain-chainlit** contains a sample chatbot application built using a SQL database in Microsoft Fabric as a vector store and search. It leverages Langchain and Chainlit for interacting with large language models (LLMs) and providing a chat interface1.

The solution works both locally and in Azure, and it is composed of three main Azure components:

1. **Fabric SQL Database**: This database stores the data.
2. **Azure Open AI**: This service provides the language model that generates text and embeddings. It requires two models: one for generating embeddings (recommended model: text-embedding-3-small) and one for handling the chat (recommended model: gpt-4 turbo).
3. **Azure Functions**: These serverless functions automate the process of generating embeddings, although this is optional for the sample2.

The repository includes detailed instructions on setting up the environment, deploying the database, and configuring the Azure OpenAI service. It also provides a .NET 8 Core console application for deploying the database or the option to deploy it manually.

This repository contains the Back From Ignite France 2024 video presenting the deployment of the above sample linked to gpt4o and ada2 models.

[Microsoft-Fabric-Database-and-RAG-application/FabricDBRAG.mp4 at main · fredgis/Microsoft-Fabric-Database-and-RAG-application](https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/FabricDBRAG.mp4)

<video width="320" height="240" controls>
  <source src="https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/FabricDBRAG.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>