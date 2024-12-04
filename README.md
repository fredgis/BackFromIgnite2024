# Microsoft Fabric Databases - Back From Ignite 2024

This GitHub repository is linked to **Azure-Samples/fabric-rag-langchain-chainlit** contains a sample chatbot application built using a SQL database in Microsoft Fabric as a vector store and search. It leverages Langchain and Chainlit for interacting with large language models (LLMs) and providing a chat interface1.

The solution works both locally and in Azure, and it is composed of three main Azure components:

1. **Fabric SQL Database**: This database stores the data.
2. **Azure Open AI**: This service provides the language model that generates text and embeddings. It requires two models: one for generating embeddings (recommended model: text-embedding-3-small) and one for handling the chat (recommended model: gpt-4 turbo).
3. **Azure Functions**: These serverless functions automate the process of generating embeddings, although this is optional for the sample2.

The repository includes detailed instructions on setting up the environment, deploying the database, and configuring the Azure OpenAI service. It also provides a .NET 8 Core console application for deploying the database or the option to deploy it manually.

This repository contains the Back From Ignite France 2024 video presenting the deployment of the above sample linked to gpt4o and ada2 models.

[Microsoft-Fabric-Database-and-RAG-application/FabricDBRAG.mp4 at main · fredgis/Microsoft-Fabric-Database-and-RAG-application](https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/FabricDBRAG.mp4)

<p align="center">
  <img src="https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/FabricDatabase.png" alt="Microsoft Fabric Databases" width="400" style="border: 1px solid lightblue; margin-right: 20px;"/>
  <img src="https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/FabricVector.png" alt="Your Second Image" width="400" style="border: 1px solid lightblue;"/>
</p>



<p align="center">
  <img src="https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/FabricChainlit.png" alt="Microsoft Fabric Databases" width="400" style="border: 1px solid lightblue; margin-right: 20px;"/>
  <img src="https://github.com/fredgis/Microsoft-Fabric-Database-and-RAG-application/blob/main/Fabric4o.png" alt="Your Second Image" width="400" style="border: 1px solid lightblue;"/>
</p>

[Microsoft Fabric - De l’analyse à la mise en place d’une plateforme de données unifiée (fabricbook.fr)](https://fabricbook.fr/)

<p align="center">
  <img src="https://fabricbook.fr/assets/couverture.jpg" alt="Couverture du livre" width="400" style="border: 1px solid lightblue;"/>
</p>


- Chapitre 01: Introduction à Microsoft Fabric
- Chapitre 02: Démarrer avec Fabric
- Chapitre 03: Du Lakehouse à la première analyse
- Chapitre 04: Unifier des données dans OneLake
- Chapitre 05: Ingérer des données dans Fabric
- Chapitre 06: Transformations avancées des données
- Chapitre 07: Organiser des données entre Datawarehouse et Lakehouse
- Chapitre 08: Traiter et analyser des données en temps réel
- Chapitre 09: Concevoir des Modèles sémantiques
- Chapitre 10: Analyse et reporting d'entreprise
- Chapitre 11: Utiliser l'IA dans Fabric
- Chapitre 12: Collaborer en équipe avec Fabric
- Chapitre 13: Architecture
- Chapitre 14: Sécuriser sa plateforme de données
- Chapitre 15: Administrer Fabric
- Chapitre 16: Maîtriser et optimiser les coûts
