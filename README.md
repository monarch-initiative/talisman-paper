[![DOI](https://zenodo.org/badge/13996/monarch-initiative/enrichgpt-results.svg)](https://zenodo.org/badge/latestdoi/13996/monarch-initiative/enrichgpt-results)

# Large Language Models for Gene Set Summarization

Molecular biologists frequently need to interpret large gene lists derived from high-throughput experiments. This is typically done as an enrichment analysis, an operation that summarizes the most salient gene functions or properties. These analyses currently make use of curated knowledge base assertions, frequently using an ontology such as the Gene Ontology. Interpreting gene lists can also be framed as a text summarization task, enabling the use of Large Language Models (LLMs) such as GPT. These models are able to perform higher order pattern matching over input texts, as well as draw from a massive corpus of background texts, including scientific texts and databases describing genes and their functions.

We explored the ability of LLMs to perform gene description summarization as a proxy for term enrichment, using both structured text derived from curated ontology annotations, and unstructured gene summaries. We compared results against robust statistical over-representation methods, and qualitatively analyzed the results.

## Folder layout

The core results are here:

[results/human/gpt4](results/human/gpt4)

each yaml file contains results for gpt4, gpt-3.5-turbo, and text-davinci-003
