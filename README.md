# King Lear RAG System

This repository accompanies an in-progress research project by Junting Huang and Teddy Roland. The project investigates whether Large Language Models (LLMs) can produce contextually grounded literary interpretations by reframing Retrieval-Augmented Generation (RAG) through the lens of Wittgenstein and Cavell's ordinary language philosophy.

Using *King Lear* as a case study, we design a custom RAG pipeline to test how LLMs retrieve, cite, and interpret literary evidence when answering factual, ambiguous, and counterfactual questions. This repository includes implementation notebooks, evaluation metrics, and experimental data.

## Notebooks

Exploratory data analysis and evaluation notebook for RAG-based responses.

## Folder Structure
- data/
  - kinglear.tsv
  - null-generate.tsv
  - rag-retrieval.tsv
  - rag-generate.tsv
- notebooks/
  - rag_eda.ipynb
- outputs/
  - rag-generate_with_accuracy.tsv
  - rag-generate_a_classified.tsv
  - combined_accuracy_evaluation.tsv
- README.md
