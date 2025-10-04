# Tracing Basics README

## Summary of Learnings

This notebook covers the fundamentals of LangSmith tracing using the @traceable decorator, demonstrating how to trace RAG applications, add metadata to runs both statically and at runtime, and properly structure trace hierarchies for comprehensive monitoring.

## Code Tweaks

Added metadata parameters to the @traceable decorators for retrieve_documents and call_openai functions, including vectordb and model information, and implemented runtime metadata addition through langsmith_extra parameters.