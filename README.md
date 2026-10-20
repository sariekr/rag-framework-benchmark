# RAG Framework Benchmark

A comparison of LangChain, LangGraph, LlamaIndex, Haystack, and DSPy implementing the same agentic retrieval-augmented generation workflow.

[Read the benchmark on AIMultiple](https://aimultiple.com/rag-frameworks).

The study holds the model, embedding model, vector store, web search provider, and core workflow decisions consistent across implementations. This makes it possible to examine framework overhead and token consumption within a shared task.

The workflow includes routing, retrieval, evidence grading, and answer generation. Instrumentation separates time spent in external model and tool calls from time spent in orchestration. Token accounting covers the model calls made throughout the workflow.

The published report explains the shared constraints and the implementation differences that remain. Framework-specific optimizers and alternative architectures can change performance. The results therefore describe this standardized pipeline, model configuration, and question set. The article also discusses the development experience of expressing the same workflow in each framework.

The benchmark implementation was developed for AIMultiple and belongs to AIMultiple. This repository is a documentation summary. Source code and benchmark datasets are not distributed here.
