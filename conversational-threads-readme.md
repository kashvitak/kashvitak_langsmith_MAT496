# Conversational Threads README

## Summary of Learnings

This notebook demonstrates how to implement conversational threads in LangSmith to track multi-turn conversations by linking traces together using unique thread identifiers (thread_id, session_id, or conversation_id) passed through metadata.

## Code Tweaks

Modified the system prompt to specify "answer tasks related to Langsmith and Langchain" and changed one of the test questions from "How can I add tags to a Trace?" to "Are tags same as Unique ID?" to explore different aspects of the tracing system.