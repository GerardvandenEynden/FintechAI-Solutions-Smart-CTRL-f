# FintechAI-Solutions-Smart-CTRL-f
This is a small model that searches for paragraphs in legal documents. The text is transformed into embeddings using SBERT from HuggingFace. They are then compared to a template-paragraph (also an embedding) and a cosine-similarity score is calculated indicating the correct paragraph. This can not be done with a simple CTRL-f.

n.b.: eerst een README.md file in de repo aanmaken en commit changes
n.b.: clear all output in Colab Notebook (voorkomt invalid notebook warning)
