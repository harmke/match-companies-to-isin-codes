# Match company names to ISIN codes using Azure AI Language and Wikidata

This example notebook uses the Azure AI Language service to link company names to company ids (ISIN codes) using Wikidata. The notebook is divided into the following sections:
- Import libraries
- Util functions
- Get ISIN codes from list of wikipedia pages
- Get linked entities from text using Azure AI Language
- Function to get ISIN codes from text
- Get ISIN codes for each document in `data` folder

Please refer to this page for more information on the Azure AI Language entity linking capabilities: https://learn.microsoft.com/en-us/azure/ai-services/language-service/entity-linking/quickstart?tabs=windows&pivots=programming-language-python
