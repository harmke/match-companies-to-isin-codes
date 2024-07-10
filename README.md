# Match names to ISIN codes using Azure AI Language and Wiki data

Entity linking is a natural language processing task that involves identifying and disambiguating entities in a text. Entities are words or phrases that refer to real-world objects, such as people, places, organizations, events, products, etc. Disambiguating entities means resolving the ambiguity that arises when the same word or phrase can refer to different entities, depending on the context. For example, the word "Apple" can refer to the fruit, the company, or the Beatles' record label, depending on the text.

Entity linking is important for many applications, such as information extraction, knowledge graph construction, question answering, text summarization, and sentiment analysis. By linking entities to their unique identifiers in a knowledge base, such as Wiki data, we can enrich the text with additional information and enable semantic search and reasoning.

This example notebook uses the Azure AI Language service and Wiki data to link company names mentioned in unstructured text (e.g. news articles or transcriptions of earning calls) to company ids (ISIN codes). 

The notebook is divided into the following sections:

- Import libraries
- Util functions
- Get ISIN codes from list of wikipedia pages
- Get linked entities from text using Azure AI Language
- Function to get ISIN codes from text
- Get ISIN codes for each document in `data` folder

Please refer to this page for more information on the Azure AI Language entity linking capabilities: https://learn.microsoft.com/en-us/azure/ai-services/language-service/entity-linking/quickstart?tabs=windows&pivots=programming-language-python