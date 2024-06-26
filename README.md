# Multi-AI-Agent-Systems
Streamlit + 
- Multi AI Agent Systems with crewAI
- Multimodal Search and RAG with Weaviate
- Agentic RAG with LlamaIndex
- RAG with Mistral
- Knowledge Graphs for RAG with neo4J
- Prompt Engineering with Llama 2 & 3
- Applications with Vector Databases with Pincone
- LLM Apps with LangChain.js

## Get an OpenAI API key
You can get your own OpenAI API key by following the following instructions:

- Go to https://platform.openai.com/account/api-keys.
- Click on the + Create new secret key button.
- Next, enter an identifier name (optional) and click on the Create secret key button.

## Set the OpenAI API key as variable in Streamlit Community Cloud

- In the lower right corner, click on Manage app.
- Click on the vertical "..." and then select Settings.
- In the App settings, navigate to the Secrets tab.
> OPENAI_API_KEY='xxxxxxxxxx'.

## Run locally
- Create a virtual environment with virtualenv .venv.
- Activate the virtual environment using source .venv/bin/activate.
- Install the required dependencies with pip install -r requirements.txt.
- Start the Streamlit app by running
> streamlit run Chatbot.py.
