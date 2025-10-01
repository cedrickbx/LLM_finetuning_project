# LLM_finetuning_project
This repository is for CS614 Assignment 1 task - perform extended LLM training/ finetuning

#Task Description:
This project will focus on using a decoder-only LLM to summarise texts, where normally an encoder-decoder LLM is better suited for this task due to its ability to understand the input (via the encoder) and generate text based on the contextual abstraction (via the decoder). The objective of this project is to enhance the performance of the decoder-only LLM through training.

#Evaluation Metric Used:
BERTScore - sum of cosine similarity of input and output embeddings to determine semantic similarity. This is used instead of metrics such as ROUGE as BERTScore is able to detect paraphrasing in the summaries which will be able to reflect the performance of the LLM better.
