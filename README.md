# Langchain RAG Tutorial.

## Install Poetry.

Head to the poetry website and follow the instructions based on your system.
https://python-poetry.org/docs/

```python
poetry config virtualenvs.in-project true
```

```python
poetry install
```

```python
poetry shell
```

## Create database.

Create the Chroma DB.

```python
python3 create_database.py
```

## Query the database.

Query the Chroma DB.

```python
python3 query_data.py "How does Alice meet the Mad Hatter?"
```

> You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.

Here is a step-by-step tutorial video: [RAG+Langchain Python Project: Easy AI/Chat For Your Docs](https://www.youtube.com/watch?v=tcqEUSNCn8I&ab_channel=pixegami).