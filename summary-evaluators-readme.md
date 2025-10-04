# Summary Evaluators README

## Summary of Learnings

This notebook demonstrates how to create summary evaluators that operate on entire experiment datasets rather than individual examples, specifically implementing F1-score calculation for toxicity classification with precision and recall metrics.

## Code Tweaks

Added weighted F1-score calculation to handle class imbalance and implemented macro-averaging across multiple classes, plus introduced threshold tuning for optimized classification performance based on validation data.