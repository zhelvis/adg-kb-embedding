# Adguard KB Embeddings

## Overview

This repository contains the code for creating and evaluating the embeddings for the [Adguard Knowledge Base](https://github.com/AdguardTeam/KnowledgeBase).

Compiled data in `dist/embeddings.csv`

This project is heavily inspired by [Open AI Website QA tutorial](https://platform.openai.com/docs/tutorials/web-qa-embeddings).

## Installation

Create a `.env` file in the root directory and add the following variables:

```
GITHUB_API_TOKEN=your_github_access_token
OPENAI_API_KEY=your_openai_api_key
```

Create and activate a python virtual environment, then install the requirements:

```
python -m venv env

source env/bin/activate

pip install -r requirements.txt
```
