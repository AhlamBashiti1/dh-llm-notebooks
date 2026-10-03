# Large Language Models for Digital Humanities: Python Notebooks

Practical notebooks for students of the Digital Humanities. **No programming or AI background is needed.**
Every notebook runs in Google Colab, uses examples from history, books and archives, and works in **English and Arabic**.

## The notebooks

| # | Topic | Open in Colab | Needs | Key |
|---|---|---|---|---|
| 1 | Embeddings and similarity | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/01_embeddings_and_similarity.ipynb) | free CPU | none |
| 2 | What is a vector database | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/02_vector_database.ipynb) | free CPU | none |
| 3 | Claude, OpenAI and Gemini APIs | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/03_llm_api_prompting.ipynb) | free CPU | one API key |
| 4 | RAG with static demonstrations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/04_rag_static_demonstrations.ipynb) | free CPU | one API key |
| 5 | RAG with a vector database | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/05_rag_vector_db.ipynb) | free CPU | one API key |
| 6 | Open-weight models and prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/06_open_weight_models.ipynb) | free T4 GPU | none Model: Qwen2.5-3B-Instruct |
| 6 | Open-weight models and prompting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/06_open_weight_modelsLLama.ipynb) | free T4 GPU | none Model: Llama-3.2-3B-Instruct|
| 7 | RAG with an open-weight model | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/07_rag_open_weight_models.ipynb) | free T4 GPU | none |
| 8 | Translation, summarisation, sentiment, NER, relations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/08_task_specific_examples.ipynb) | free CPU | Claude API key |
| 8 | Translation, summarisation, sentiment, NER, relations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/08_FreeTier_Task_specific_examples.ipynb) | free CPU | Gemini API key |
| 9 | Testing a model on your own task | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhlamBashiti1/dh-llm-notebooks/blob/main/notebooks/09_benchmark_sentiment.ipynb) | free T4 GPU | none |


## Testing status (Notebook tested Status): [Testing checklist](https://github.com/AhlamBashiti1/dh-llm-notebooks/issues/1)

## How to use them

1. Click **Open in Colab** next to a notebook (you need a free Google account).
2. For notebooks that need a GPU: *Runtime > Change runtime type > T4 GPU > Save*.
3. Run the cells from top to bottom (`Shift+Enter`). Lines that start with `#` are comments that explain the code.

Suggested order: 1, 2, then 3, 4, 5 (with an API model), or 6, 7 (free open-weight model). Notebooks 8 and 9 can follow either path.

## API keys

Notebooks 3, 4, 5 and 8 call a commercial model and need **your own** API key. Notebook 3 explains how to create one and how to save it safely in Colab Secrets (the key icon in the left sidebar). **Never paste a key into a cell and never commit a key to GitHub.**

## Data

The `data/` folder holds the small example collections used in the notebooks (the notebooks contain their own copy, so they run without downloading anything):

- `heritage_passages.json`: 14 short historical passages in English and Arabic
- `cedar_valley_archive.json`: an **invented** archive (12 records, English and Arabic) used for RAG
- `archive_comments_labelled.json`: 24 **invented** labelled comments used for the benchmark

## Good habits

Verify what models say, record your prompts, model names and settings, and do not send private or restricted material to an online service unless your ethics approval allows it.

## Authors and licence

To be added.
