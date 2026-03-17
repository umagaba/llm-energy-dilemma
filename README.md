# The LLM Energy Dilemma: Performance vs Carbon Emissions Trade-off

This project investigates the trade-off between **performance and carbon emissions** when using Large Language Models (LLMs) versus fine-tuned Small Language Models (SLMs).

The study evaluates whether smaller models can achieve competitive performance for specific tasks while dramatically reducing inference emissions.

## Tasks Evaluated

- English → French Translation
- Short Story Generation
- Python Code Summarization

## Models

### Small Language Models (fine-tuned)
- GPT-2
- DistilGPT2
- Pythia
- CodeT5
- CodeParrot
- TinyCodeLM
- Helsinki-NLP translation models
- T5-small

Model sizes: **60M – 160M parameters**

### Large Language Models (API)
- Mistral-7B
- Qwen-235B
- DeepSeek-671B

## Methodology

1. Fine-tuned small models on task-specific datasets
2. Benchmarked performance against large LLM APIs
3. Measured inference emissions using **eco2AI**
4. Compared performance vs energy trade-offs

## Datasets

- OPUS English-French
- WritingPrompts
- CodeSearchNet

## Key Results

- Fine-tuned SLMs improved performance by:
  - **28% (translation)**
  - **15–20% (story generation)**
  - **25% (code summarization)**

- Inference emissions:
  - **SLMs:** ~0.005–0.01 g CO₂/query  
  - **LLMs:** up to ~3.6 g CO₂/query

- Emissions reduction:
  - **660× – 13,000× lower**

## Paper

Accepted at **IEEE FLLM 2025 – Vienna**

## Tech Stack

Python  
PyTorch  
HuggingFace Transformers  
eco2AI  
Pandas  
NumPy

## Repository Structure
models/
training/
evaluation/
emissions_tracking/
notebooks/
