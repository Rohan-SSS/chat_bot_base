# Personalized Chat bot

## Description

This project is a base for creating a personalized chatbot, which uses OpenAI's gpt model to chat with users. The documentation of the appliaction is used to form embeddings using OpenAI's embedding model, and these embeddings are stored in Pinecone's Vector DB, and this DB is the knownledge base of the application where you can run queries. Queries can be personalised for better results. All of this is mainly done using LangChain llm library.

## Pre-requisite

1. OpenAI API key, get here [OpenAI](https://openai.com/)
2. Pinecone API key, get here [Pinecone](https://www.pinecone.io/)

## Installation

Clone the repo

```bash
git clone
cd chat_bot_base
```

Create venv and install req.

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

## Uage

Add your credentials to **.env**

```bash
source .env
```

Run the **main.ipynb** cells
