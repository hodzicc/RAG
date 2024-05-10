# RAG
A simple Retrieval-Augmented Generation (RAG) system with conversational history tracking.

This Colab notebook is a work in progress, and improvements are ongoing. It demonstrates the implementation of a history-aware language model using Llama2 and Chromadb. The model is designed to generate responses based solely on the context provided, ensuring relevance and accuracy without relying on its pre-trained general knowledge. This project aims to refine how the model handles conversation history, focusing on generating responses and search queries relevant to the user's input.

Features:

-History-Aware Retriever: Generates search queries based on the current conversation context and the user's latest question.

-Contextual Response Generation: Answers questions using only the specified context and explicitly avoids using external knowledge unless it's provided in the context.

-Prompt Refinement: Utilizes carefully crafted prompt templates to guide the model's responses strictly.
