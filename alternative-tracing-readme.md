# Alternative Tracing Methods README

## Summary of Learnings

This notebook explores various methods for implementing tracing in LangSmith beyond the standard @traceable decorator, including environment variable setup for LangChain/LangGraph, trace context managers, automatic OpenAI call tracing with wrap_openai, and the advanced RunTree API for manual trace control.

## Code Tweaks

I customized the final RunTree example by modifying the system prompt to adopt a specific persona and adjusted the LLM's temperature to generate more creative responses.