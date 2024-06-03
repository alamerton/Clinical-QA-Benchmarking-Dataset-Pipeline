# Benchmarking Dataset for Clinical Question Answering Large Language Models
This is the repo for my MSc individual project: **Production of a Benchmarking Dataset for Clinical Decision Reasoning Question-Answering Large Language Models**. This repo contains the dataset generation code for the dataset. The high-level steps for the production of the dataset using this code are as follows:
1. Implementing the emrQA dataset generation framework from their paper
2. Modifying the framework to create a dataset using the MIMIC-III data
3. Developing the dataset based on the comparative analysis of the other major clinical QA benchmarking datasets, addressing their flaws
4. Augmenting and expanding the dataset using LLMs. Techniques I am currently considering for question-answer generation and annotation are retrieval-augmented generation (RAG) and scalable oversight
5. Benchmarking the clinical QA capabilities of LLMs, in terms of decision reasoning using electronic health records, using the dataset
