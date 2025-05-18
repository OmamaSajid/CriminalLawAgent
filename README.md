# Criminal Law Agent
⚖️ **Enjoy having your own AI-powered criminal law assistant!**  

An AI-powered agent for criminal law research and question answering using Astra DB and a custom LLM-based pipeline.


## Features

- Ingest and index documents into Astra DB
- Chunk text for efficient retrieval
- Semantic search using vector similarity
- Retrieval-Augmented Generation (RAG)
- Customizable prompt templates
- Structured output parsing

## Requirements

- Python 3.10+
- Astra DB credentials
- LLM API key (e.g., OpenAI, Anthropic)
- `pip` or `poetry` for dependency management
##INSTALLATION:
git clone https://github.com/OmamaSajid/CriminalLawAgent.git
cd criminal-law-agent
pip install -r requirements.txt
# or
poetry install
##USUAGE
python main.py

## Environment Setup

Copy `.env.example` to `.env` and provide the required credentials:

```env
ASTRA_DB_APPLICATION_TOKEN=your_astra_token
ASTRA_DB_CLIENT_ID=your_client_id
ASTRA_DB_CLIENT_SECRET=your_client_secret
ASTRA_DB_KEYSPACE=criminal_agent

LLM_PROVIDER_URL=https://api.your-llm-provider.com/v1
LLM_API_KEY=your_llm_api_key

CHUNK_SIZE=1000
CHUNK_OVERLAP=200
TOP_K_RESULTS=5

