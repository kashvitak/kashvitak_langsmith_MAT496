# Types of Runs README

## Summary of Learnings

This notebook demonstrates the different run types in LangSmith (LLM, Retriever, Tool, Chain, Prompt, Parser) and their specific formatting requirements, including proper input/output structures for chat models, document retrieval, and tool calling with custom rendering support.

## Code Tweaks

Added run_type parameters to various @traceable decorators (llm, retriever, tool), included ls_provider and ls_model_name metadata for proper model identification, and implemented reduce_fn for streaming LLM responses to aggregate chunked outputs.