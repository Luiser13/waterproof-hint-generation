# Waterproof Hint Generation 

## Overview
Extended a formal proof-writing system with context-conditioned hint generation, using LLM-based synthesis grounded in proof state and goal structure.

## Contribution
- Evaluated deterministic (e.g. Graph2Tac) vs generative (LLM-based) approaches for proof assistance
- Designed and implemented an LLM-based hint generation pipeline conditioned on:
- - current proof state
- - target proof goals
- Engineered structured prompting to control output granularity, format, and consistency
- Integrated the pipeline within the proof environment and editor layer 

## Hint Generation Modes
- Full solution synthesis (stepwise proof completion)
- Natural language guidance (conceptual direction)
- Formal mathematical hints (symbolic structure)
- Hybrid outputs (formal + explanatory reasoning) 

## Technical Stack
- Rocq / Coq (proof state extraction and interaction)
- TypeScript (editor / extension integration)
- LLM-based generation and prompt design 

## Notes 
The underlying repository is privately hosted and not under my ownership, so I cannot share the code publicly.
Developed under the supervision of Jim Portegies (TU Eindhoven) in 2024. 
I’m happy to discuss my contributions in detail.
