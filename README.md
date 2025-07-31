# LLM Ranking Analysis

A visualization of major LLMs (Large Language Models) ranked by performance, using MMLU (Massive Multitasks Language Understanding) which is a benchmark for evaluating the capabilities of LLMs.

[Dashboard](https://public.tableau.com/app/profile/waqas5688/viz/LLMRanking/Dashboard)

![Dashboard](https://github.com/qureshiwaqas/llm-ranking-analysis/blob/main/resources/dashboard.png)

## Data 
[Data Source](https://docs.google.com/spreadsheets/d/1kc262HZSMAWI6FVsh0zJwbB-ooYvzhCHaHcNUiA0_hY/edit?usp=sharing)

[My data](https://github.com/qureshiwaqas/llm-ranking-analysis/blob/main/resources/My%20Data.xlsx)

Note : The MMLU rating is based on results from 16,000 multiple-choice questions across 57 academic subjects. While language models can be pre-trained on MMLU-style questions, it still serves as a strong benchmark for evaluating a model’s overall capability.

## Insights Derived 

Anthropic entered the market in June 2023 and in June 2024 released Claude Sonnet 3.5, quickly setting a new industry standard for AI-assisted coding.

DeepSeek (China), with its R1 model, matches the performance of OpenAI’s o1 using a MoE architecture (~37 B active), proving far more efficient; distilled Qwen‑models offer near‑state‑of‑the‑art results with much smaller footprints.
Alibaba’s Qwen series are open‑source, support MoE, and claim performance comparable to R1 in math, coding and reasoning tasks 

Google DeepMind’s Gemma models, released since early 2024, are open-source (Gemma 3), efficient, multilingual and support multimodal input, but top-tier closed models remain unavailable.

Meta’s LLaMA (up to 65 B) and LLaMA 3 (405 B) are open‑source and deliver top-tier performance in text and code, making Meta a leader in accessible quality models.

Microsoft’s GRIN MoE, though later to market, demonstrates that sparse models can match larger dense models with only ~6–7 B active parameters. However, these models remain closed and have not yet achieved mainstream impact.

Mistral’s open-source models, such as Mistral Large 2, balance parameter efficiency with near‑human‑level expertise in reasoning and code.

OpenAI’s models remain among the most powerful, though often parameter-heavy. Studying models like DeepSeek or Mistral may help reduce parameter usage without compromising quality.
