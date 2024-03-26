# Data-Science-AI-Assistant

**AI Assistant** that can accomplish the task of **"Explaining or teaching basic data science concepts,"** 

This project is also an occasion to explain how a basic **retrieval-augmented generation (RAG)** system works, by showing the role of the data, which constitutes the backbone of the system, the function of embeddings and distance measures, how to retrieve relevant information for the task of answering a question, and how to process such information by first using a distillation prompt and then assembling the answer required by the user in a meaningful and useful way.

In this project, the lion's share is done by **Gemma**, the state-of-the-art open LLM model released by Google, in its <U>2b-it implementation, the smallest in terms of parameters</U>. Gemma is not the only Google technology presented in the project because I also make use of **ScaNN** ([ScaNN Github repository](https://github.com/google-research/google-research/tree/master/scann)) for recalling the information. Apart from Gemma, ScaNN, and HuggingFace packages for transformers and embeddings, there are no ready-made solutions such as vector stores or RAG packages. You can actually see how everything works under the hood, and if you like it, reuse it for your own projects.
