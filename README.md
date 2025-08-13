# MCP Client using Azure AI Foundry Agent Service with Azure Function App


## Running the Azure AI Foundry Agent Service MCP Client

Save the file `.env_sample` as `.env` and update the environment variables. 

## Update the .env file. Samples are

MODEL_DEPLOYMENT_NAME= gpt-4o
<br>
PROJECT_ENDPOINT=https://[ai foundry service].services.ai.azure.com/api/projects/Project01
<br>
MCP_SERVER_URL=https://[azure function app].eastus-01.azurewebsites.net/runtime/webhooks/mcp/sse
<br>
MCP_SERVER_KEY= [mcp extention key]

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









