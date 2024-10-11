# 💬 Multi-Agent RAG Workshop

A simple Streamlit app that shows how to build a chatbot using multiple agents.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://multi-agent-rag.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```



# Documentation
- Github: https://github.com/AI-Maker-Space/LLAMAINDEX-RAGATHON-WORKSHOP24

## Endpoints
- Hugginface Inference Endpoints
- Text Generation Inference
- Read 01-Readme
- My Endpoint: https://uc154cthxapsiuya.us-east-1.aws.endpoints.huggingface.cloud

## Chat Model

### Llamaparse
- document parser for the contet augmentation

### Models
LLama 3.1
Mistral Embed for embedding Model

## Vector DB
- Pinecone 
- - Long-term memory for high-performance AI 
- - Setup P1 Pods 

<hr />

# AI Makerspace Workshop: Building Multi-Agent Applications with LlamaIndex and Llama 3.1

# 📊 **Technical Level** 4/7

# 🧑‍💻 Workshop Description

As agents have taken over the AI scene in 2024, companies like LlamaIndex that create developer tools for orchestrating complex agentic LLM applications have learned valuable lessons about the best way to implement agentic behavior.

In this worshop, we’ll cover the latest and greatest implementation used by LlamaIndex Workflows: ***Event-Driven Architecture (EDA*)**. This technique for creating agentic applications stands out above the chain and pipeline implementations that use Directed Acyclic Graphs (DAGs) as well as the cyclic graph approaches that have been gaining in popularity.  

During this workshop, we’ll break down each of the core constructs within LlamaIndex Workflows, which fundamentally are made up of **steps** (i.e., ****Python functions).  Each step is responsible for handling certain event types and emitting new events.

Join us to get out ahead of the hackathon and learn the the concepts and boilerplate code you need to understand and build a complex agentic application with LlamaIndex!

# 📚 **Prerequisite Knowledge**

- Working knowledge of how to run Machine Learning Python code in Jupyter Notebooks
- Practical knowledge of how to use an interactive development environment with version control so that you can engage with our public GitHub repo.  To test yourself, complete [The AI Engineering Bootcamp Challenge](https://aimakerspace.journey.io/p/aie-challenge)

## 📛 Required Account Set-Ups

- 🤗 Hugging Face
    
    You will need access to a [Hugging Face account](https://huggingface.co/login) to download model weights
    
- 💬 OpenAI API
    
    You must enable billing through [the OpenAI API](https://help.openai.com/en/collections/3675945-understanding-openai-api-billing-usage), which we will use throughout the workshop.
    
- 🌲 Pinecone
    - Create a [Pinecone account](https://login.pinecone.io/login) and set up your API key.
- 🦙 (Optional) Llama 3
    
    We’ll use completely open-sourced versions of Llama 3.1 (e.g., from [NousResearch](https://huggingface.co/NousResearch/Meta-Llama-3.1-8B-Instruct)). However, to use the models [directly from Meta](https://huggingface.co/meta-llama), you’ll need to share your contact information with Meta.  You can find the Meta model [here](https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct).
    

## **👨‍🏫 Concepts**

We’ll cover:

- Prototyping patterns of GenAI, including Prompt Engineering, RAG, Fine-Tuning, and Agents
- Understand agents and agentic behavior as a pattern of reasoning and action
- The big ideas behind giving agents access to tools through [Function Calling](https://openai.com/index/function-calling-and-other-api-updates/)
- When multiple agents can add value to your product or application
- The core ideas and constructs you’ll need to build agent applications with LlamaIndex

## ⌨️ **Code**

You’ll learn how to:

- 🤗 Leverage open-source LLMs from Hugging Face
- ⛓️ Build custom agent applications with LlamaIndex
- 🤖 Develop agentic workflows with Workflows and the OpenAI function calling API

### **🧰 Tools**

We’ll use the following tooling:

- LLM Chat Model: [Llama-3.1-8B-instruct](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct)
- Embedding Model: [Snowflake-arctic-embed-m](https://huggingface.co/Snowflake/snowflake-arctic-embed-m)
- Vector Database: [Pinecone](https://docs.pinecone.io/guides/get-started/quickstart)
- Orchestration: [LlamaIndex](https://docs.llamaindex.ai/en/stable/module_guides/workflow/)
- Agents: [Workflows](https://docs.llamaindex.ai/en/stable/module_guides/workflow/)
- Data: “Elon Musk vs. The People of Earth,” An AI Makerspace custom dataset of X/Twitter beefs (e.g., with Mark Zuckerberg, Yann Lecun, OpenAI, and more!).

# Learning Outcomes

📚 You’ll learn:

- The core concepts and code for LlamaIndex Workflows
- How to build state-of-art agents in LlamaIndex using an event-driven architecture
- How to create multi-agent architectures using reflection and error correction.

🤓 Who should attend the event:

- Aspiring AI Engineers who want to build at the open-source edge with LlamaIndex
- AI Engineering leaders who want to learn the most popular open-source agent frameworks