# MCP Client using Azure AI Foundry Agent Service with Azure Function App


## Running the Azure AI Foundry Agent Service MCP Client

Save the file `.env_sample` as `.env` and update the environment variables. 

## Login to Azure


az account clear

az login --tenant <tenant id if you have more that one tenant> 

az account set --subscription <subscription id where AI Foundry exists anf if you have more than one subscription in the account>                                                         

## Run the following commands
```
uv venv
uv sync
uv run sample_agents_mcp.py
```

## output screen shots

<img width="1920" height="814" alt="Screenshot 2025-08-13 193442" src="https://github.com/user-attachments/assets/5db874c0-2250-4489-8576-e048ac793767" />




