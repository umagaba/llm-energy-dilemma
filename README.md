# The LLM Energy Dilemma: Performance vs Carbon Emissions Trade-off

This project investigates the trade-off between **performance and carbon emissions** when using Large Language Models (LLMs) versus fine-tuned Small Language Models (SLMs).

The study evaluates whether smaller models can achieve competitive performance for specific tasks while dramatically reducing inference emissions.

## Tasks Evaluated

- English → French Translation
- Short Story Generation
- Python Code Summarization

## Models

#(All mentioned models hosted on Kaggle)

# CONTENT CREATION (STORY WRITING)

DATASET - Writing Prompts Dataset (https://huggingface.co/datasets/euclaise/writingprompts) 

Pythia (160M) 
https://www.kaggle.com/models/umagaba/content-creation-eleutheraipythia-160m

DistilGPT2 (82M)
https://www.kaggle.com/models/umagaba/content-creation-distilgpt2

GPT-2 (137M)
https://www.kaggle.com/models/umagaba/content-creation-gpt2

# TRANSLATION (ENGLISH TO FRENCH)

DATASET - opus-en-fr

t5-small (60.5M)
https://www.kaggle.com/models/umagaba/translation-t5-small

Helsinki-NLP/opus-mt-en-ROMANCE
https://www.kaggle.com/models/umagaba/translation-helsinki-nlpopus-mt-en-roman

Helsinki-NLP/opus-mt-en-fr
https://www.kaggle.com/models/umagaba/translation-helsinki-nlpopus-mt-en-fr

CODE SUMMARIZATION (PYTHON)

DATASET - codesearchnet
https://huggingface.co/datasets/sentence-transformers/codesearchnet

codet5-small (60M)
https://www.kaggle.com/models/umagaba/code_summarization-codet5-small

codeparrot-small (110)
https://www.kaggle.com/models/umagaba/code-summarization-codeparrot-small

TinyCodeLM (150M)
https://www.kaggle.com/models/umagaba/code-summarization-tinycodell

### Large Language Models
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

<img width="2000" height="1414" alt="3" src="https://github.com/user-attachments/assets/544d61be-12be-4f1d-9321-2861dfbe3a5a" />

<img width="2000" height="1414" alt="6" src="https://github.com/user-attachments/assets/7fb20d84-d956-403b-b8d1-5d2e16d10ce6" />

<img width="2000" height="1414" alt="7" src="https://github.com/user-attachments/assets/7f0b1712-c8d0-421e-9c60-6268920d803f" />

## Paper

Accepted at **IEEE FLLM 2025 – Vienna**

## Tech Stack

Python  
PyTorch  
HuggingFace Transformers  
eco2AI  
Pandas  
NumPy
