# LangChain-Hugging-Face-Local-Pipelines

This project demonstrates how to implement a history-aware retrieval chain using LangChain to respond to queries based on a cumulative conversation history. This approach significantly enhances the relevance and coherence of responses in interactive dialogue applications, such as virtual assistants or customer support systems.


**Use Ollama for LLM setup**
Ollama allows you to run open-source large language models, such as Llama 2, locally.
First, follow these instructions to set up and run a local Ollama instance: [Ollama](https://ollama.com/download)  
Fetch a model via ollama pull llama2


**Install the dependencies**

Create the virtual environment and install the dependencies:

```
python -m venv .venv
source .venv/bin/activate
.venv/bin/pip install -r requirements.txt
```