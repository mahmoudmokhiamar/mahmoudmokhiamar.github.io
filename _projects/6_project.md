---
layout: page
title: Sentence Highlighter with BERT Embeddings
description: Visualizing sentence similarity using BERT embeddings and cosine similarity.
img: 
importance: 1
category: work
giscus_comments: false
---

Built an interactive tool to highlight sentence similarities within documents using deep learning embeddings.

- Processed and tokenized text from `.txt` documents using NLTK's `sent_tokenize`.
- Converted sentences into embeddings with `bert-base-uncased` model from Hugging Face Transformers.
- Computed pairwise cosine similarities between sentences to detect semantic closeness.
- Generated a color-coded HTML output where similar sentences are visually highlighted.
- Fully customizable tool: supports model selection, color themes, and exportable reports.

➡️ [View Project on GitHub](https://github.com/mahmoudmokhiamar/SentenceHighlighter101)