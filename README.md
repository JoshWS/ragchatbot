# Langchain RAG Tutorial

## Install dependencies

1. Run this command to install dependenies.

```python
poetry install
```

## Create database

Create the Chroma DB.

```python
python3 create_database.py
```

## Query the database

Query the Chroma DB.

```python
python3 query_data.py "How does Alice meet the Mad Hatter?"
```

> You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.

Here is a step-by-step tutorial video: [RAG+Langchain Python Project: Easy AI/Chat For Your Docs](https://www.youtube.com/watch?v=tcqEUSNCn8I&ab_channel=pixegami).