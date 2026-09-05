# LLM From Scratch

An educational project where I build a small decoder-only language model from random initialization using PyTorch.

The goal is not to create a production-quality LLM, but to understand how language models work internally by implementing and inspecting the core components myself, including:

* tokenization and embeddings
* causal self-attention
* Transformer blocks
* next-token prediction and loss
* pretraining and validation
* autoregressive text generation
* modern LLM techniques such as RoPE, RMSNorm, GQA, efficient attention, and KV caching

The project is being developed primarily in Google Colab, with reusable components gradually moved into a clean Python codebase as they become stable.

> Work in progress — the repository will evolve alongside my understanding of LLM internals.
