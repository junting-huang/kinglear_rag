# King Lear RAG System

This repository accompanies the research project by Junting Huang and Teddy Roland, which interrogates whether Large Language Models (LLMs) can produce “real-world knowledge” by reframing the debate through Wittgenstein’s and Cavell’s philosophies of language. We analyze Retrieval-Augmented Generation (RAG) systems as computational analogues of Wittgenstein’s “five red apples” thought experiment—emphasizing that meaning in literary interpretation arises not from referential accuracy, but from social acts of acknowledgment and communal practices of attention.

Using Shakespeare’s *King Lear* as a case study, we design a custom RAG system to simulate interpretive language games, testing how LLMs retrieve, contextualize, and cite textual evidence in response to factual, ambiguous, and counterfactual questions—without claiming definitive or absolute truth. This repository contains implementation notebooks, evaluation metrics, and experimental data, supporting our argument that RAG systems, like Wittgenstein’s and Cavell’s ordinary language philosophy, may resist skepticism not by eliminating uncertainty, but by grounding knowledge in practices of acknowledgment and response within interpretive communities.

## Outputs (.tsv)
OpenAI API generated data.

## Notebooks (.ipynb)

Exploratory data analysis with OpenAI API generated data.

## Dataframes (.xlsx)

Manually sourced data.

## Folder Structure
- data/
  - kinglear.tsv
  - null-generate.tsv
  - rag-retrieval.tsv
  - rag-generate.tsv
- outputs/
  - rag-generate_with_accuracy.tsv
  - rag-generate_a_classified.tsv
  - combined_accuracy_evaluation.tsv
- rag_eda.ipynb
- rag_df.xlsx
- README.md
