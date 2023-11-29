# RAG_Q&A_LLM

In this repository, I delve into creating a **knowledge-sharing hub** from my own data sources where teams can get insights and answers with the ease of a conversation, using the RAG Q&A technique, with the potential to complete the way information is shared within both small and large organizations.

In short, **RAG Q&A** (Retrieval-Augmented Generation Question and Answering) is a framework that blends retrieval-based and generation-based approaches. It employs a retriever to find relevant information and, typically, a **LLM** (Large Language Model) as the generator to create contextually rich answers. By definition, LLMs are a type of AI model capable of understanding and generating human-like language, trained on vast amounts of text data to learn the patterns, structures, and context of natural language.

I made one notebook using the free **Llama-2–7b-chat-hf** model (with a 4-bit quantization strategy) for Google Colab, which allows running this software for free, and another notebook using the **OpenAI chat-gpt-3.5-turbo** LLM model using an OpenAI subscription.

For this use case, markdown documentation files were retrieved from three different data sources:
- [Full-Stack App Documentation](https://crowd-wire.github.io/ProjectDocumentation/): Personal project well documented with markdown files.
- [Short SQL Tables Descriptions](https://github.com/JannikArndt/sql-auto-doc/tree/master/Examples): Repository documenting some short SQL tables.
- [Demo Confluence Space](https://templates.atlassian.net/wiki/spaces/SWPRJ/overview): A public demo confluence space. The chatbot scrapes data in a markdown format.

These documents were chosen because they are typical ways for organizations to document and preserve their projects' knowledge.

**The final chatbot extracted knowledge accurately, providing concise and relevant answers, while linking the documents it used.**
