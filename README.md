**Project title :** **Arabic Summarization and Translation Using Fine-Tuned Qwen2.5-1.5B-Instruct with LoRA**

**Introduction :** This project fine-tunes Qwen2.5-1.5B-Instruct to improve Arabic article summarization and translation using LoRA, LLaMA Factory, and VLLM for efficient training and fast deployment.

**Problem Statement :** General LLMs struggle with Arabic text, often generating verbose or inaccurate results. There is a need for a lightweight, fine-tuned model that handles Arabic input effectively and provides both summaries and English translations.

**Dataset :** A custom dataset was built with Arabic articles and their corresponding English summaries/translations. Sources include Arabic news websites and manually curated content.

**Methodology :**
Base model : Qwen2.5-1.5B-Instruct

Training : Used LoRA with LLaMA Factory for efficient fine-tuning

Deployment : Used VLLM for fast inference

Additional Work : Structured output extraction with OpenAI + Pydantic and knowledge distillation to create training data

**Results :** Using a free, open-source, and lightweight model like Qwen2.5-1.5B-Instruct, we successfully achieved our goal of summarizing and translating Arabic articles.

The model produced concise summaries and fluent English translations.

Fast inference was enabled using VLLM.

High-quality distilled training data was extracted from OpenAI outputs to further enhance performance.

**Conclusion:**
The fine-tuned model improves Arabic summarization and translation. Using LoRA and knowledge distillation makes the model lightweight and effective. Future work includes reverse translation and supporting more Arabic dialects.

