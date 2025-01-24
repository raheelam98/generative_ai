# Generative AI
Generative AI uses advanced machine learning models to create realistic text, images, and audio. It can generate content for various applications, such as writing, image design, and music production. By learning from large datasets, these models improve over time, helping automate creative tasks across industries.

### Framework
A framework is a structured foundation of tools and libraries that simplifies and accelerates software development.

A framework provides a structured foundation with predefined rules and patterns for building applications, where the developer typically follows its architecture (inversion of control).

### Open-source library
An open-source library is a collection of reusable code or functions that developers can freely use, integrate, or adapt within their own project without being bound by strict architectural rules.

## LangChain
LangChain is a framework designed to build applications powered by language models, enabling tasks like chatbots, question-answering, and document analysis. It simplifies workflows by integrating tools like APIs, vector databases, and memory for seamless interaction with large language models.

## LangGraph
LangGraph is an open-source library for building stateful, multi-actor applications with Large Language Models (LLMs), enabling the creation of complex agent and multi-agent workflows. It offers fine-grained control over application flow and state, supporting features like memory persistence and human-in-the-loop interactions 

## Fine-tuning
Fine-tuning is the process of customizing a pre-trained machine learning model by training it on specific, smaller datasets to improve performance for a particular task. It allows the model to adapt its knowledge to domain-specific requirements while retaining its general capabilities.

## RAG

RAG (Retrieval-Augmented Generation) is an AI framework combining retrieval and generation, where relevant context is fetched from an external knowledge base (retrieval) to improve the quality of AI-generated responses (generation). This approach ensures accurate, context-aware outputs for tasks like Q&A or summarization.

## Embedding

[Embedding](https://developers.google.com/machine-learning/glossary#embedding-vector) is a technique used to represent information as a list of floating point numbers in an array. With Gemini, you can represent text (words, sentences, and blocks of text) in a vectorized form, making it easier to compare and contrast embeddings. For example, two texts that share a similar subject matter or sentiment should have similar embeddings, which can be identified through mathematical comparison techniques such as cosine similarity. For more on how and why you should use embeddings, refer to the [Embeddings guide](https://ai.google.dev/docs/embeddings_guide).

Use the `embed_content` method to generate embeddings. The method handles embedding for the following tasks (`task_type`):

Task Type | Description
---       | ---
RETRIEVAL_QUERY	| Specifies the given text is a query in a search/retrieval setting.
RETRIEVAL_DOCUMENT | Specifies the given text is a document in a search/retrieval setting. Using this task type requires a `title`.
SEMANTIC_SIMILARITY	| Specifies the given text will be used for Semantic Textual Similarity (STS).
CLASSIFICATION	| Specifies that the embeddings will be used for classification.
CLUSTERING	| Specifies that the embeddings will be used for clustering.

[Gemini_API_python.ipynb](https://colab.research.google.com/github/EnggQasim/5_days_AI_Agents_Training/blob/main/02_Embedding_Gemini_Mulvis/Gemini_API_python.ipynb#scrollTo=BpHIRU5bj7aW)
