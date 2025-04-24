# 🤖 Fine-Tuning GPT-2 with Hugging Face Transformers

Hi! I’m Vagif Asadov, a Computer Science student originally from Azerbaijan 🇦🇿 and currently studying in the U.S.  
This project demonstrates how to fine-tune a GPT-2-based language model using the **Hugging Face Transformers** library.

---

## 🔍 Project Overview

In this notebook, I fine-tuned **`distilgpt2`** (a lighter version of GPT-2) on a custom text dataset.  
The goal was to experiment with **causal language modeling** and understand how transformers adapt to new data.

I used Hugging Face’s `Trainer` and `TrainingArguments` for clean training workflows.

---

## ⚙️ Tech Stack

- `transformers` — for loading and fine-tuning `distilgpt2`
- `datasets` — to access or load NLP datasets
- `torch` — PyTorch backend for training
- Jupyter Notebook — for interactive experimentation

---



Things You’ll Learn From This:
How to tokenize and prepare text data for GPT-style models

How to fine-tune distilgpt2 using Hugging Face’s Trainer

How training arguments affect performance

How to generate text using your fine-tuned model


Notes:
You can replace distilgpt2 with gpt2, gpt2-medium, or other models

For larger datasets or models, consider using Colab or a GPU-backed server

Outputs were cleared to make the notebook GitHub-friendly (no metadata errors)

I'm Vagif — I love deep learning and natural language processing.
This project is part of my journey to understand real-world NLP pipelines and become industry-ready.

Feel free to check out my other projects or connect with me:

GitHub: @vagif11

LinkedIn - https://www.linkedin.com/in/asadovagif/ 
