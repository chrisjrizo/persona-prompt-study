# Persona Prompt Study

This repository contains the dataset, prompt variations, GPT-4o completions, and evaluation results for the paper:

**"Do Personas Improve Generative AI Responses? A Real-World Evaluation Using ShareGPT and GPT-4o"**

## 🔍 What’s Included

- `data/prompts_cleaned.jsonl` – subset of 4,820 ShareGPT prompts
- `analysis/persona_analysis.ipynb` – full code for scoring, regression, and visualizations
- `figs/` – key plots from the paper
- `evaluation_results.csv` – GPT-4o scores for accuracy, tone, etc.

## 📄 Dataset Schema

Each prompt entry includes:
- `id`: Unique identifier
- `user_prompt`: Original question from ShareGPT
- `task_type`: {explanation, summary, advice}
- `persona`: One of {none, basic, refined}
- `model`: `gpt-4o`
- `scores`: {accuracy, clarity, tone, summary_quality}

## 📜 License

CC BY-NC 4.0 — for academic use only.
