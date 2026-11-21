# Emotional Framing & LLM Reliability

Notebooks for testing whether emotionally framed medical questions
(from PubMedQA) affect the reliability of Claude and Gemini responses.

## Run in order
1. `01_dataset.ipynb`: load PubMedQA and build question samples
2. `02_collect_responses.ipynb`: collect model responses (needs API keys)
3. `03_analysis_results.ipynb`: score and compare responses
4. `04_graphs_figures.ipynb`: generate figures

## Setup
Create a `.env` file with your own keys:
    ANTHROPIC_API_KEY=your_key_here
    GEMINI_API_KEY=your_key_here

Dataset: PubMedQA (https://huggingface.co/datasets/qiaojin/PubMedQA, subset `pqa_labeled`)
