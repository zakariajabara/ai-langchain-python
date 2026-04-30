# ai-langchain-python
uv init
uv venv venv
source ./.venv/bn/activate

// download necesary packages
// ipykernel, tiktoken, langchain-openai, langchain, pythis-dotenv, langchain_text_splitters
// langchain_community
uv add ipykernel
uv add tiktoken

pip install langrraph
//if problems with langgraph- you can uninstall lanbraph (pip uninstall -U langgraph and instale it again) 
// than
pip install langgraph-checkpoint-sqlite 
