# Multilingual account label matching

Comparing approaches for automatically matching accounting labels
expressed in different languages against a reference chart of accounts.

## Research question

Which approach offers the best trade-off between accuracy, cost and
latency when matching multilingual accounting labels to a reference
chart of accounts?

## Approaches compared

- Exact matching after normalization
- String similarity
- Multilingual embeddings with nearest-neighbour search
- Direct LLM call on unresolved labels
- Combined pipeline

## Status

Work in progress — building the corpus.
