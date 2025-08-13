# MCP Client using Azure AI Foundry Agent Service with Azure Function App


## Running the Azure AI Foundry Agent Service MCP Client

Save the file `.env_sample` as `.env` and update the environment variables. 

az account clear
az login --tenant 16b3c013-d300-468d-ac64-7eda0820b6d3\    
az account set --subscription 1206b3f2-85a9-4a21-8fda-9c9294b8c68b                                                         


Run the following commands
```
uv venv
uv sync
uv run sample_agents_mcp.py
```


