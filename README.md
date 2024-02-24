# LLM-Fine-Tuning-Azure
A fine-tuning guide for both OpenAI and Open-Source Large Lauguage Models on Azure.

## What is LLM Fine-Tuning
Fine-Tuning, or *Supervised Fine-Tuning*, retrains an existing pre-trained LLM using example data, resulting in a new "custom" fine-tuned LLM that has been optimized for the provided task-specific examples. 
<ol><img src="labs/images/screenshot-fine-tuning-illustration-diagram.png" alt="Screenshot of What is Fine-Tuning illustration diagram." width="600"/></ol>

## Why to do LLM Fine-Tuning
Typically, we use Fine-Tuning to:
- improve model performance on specific tasks.
- introduce information that wasn't well represented by the base model.

Good use cases include: 
- steering the model outputs in a specific style or tone.
- too long or complex prompts to fit into the prompt window.

## When to do LLM Fine-Tuning
You may consider Fine-Tuning when:
- you have tried Prompt Engineering and RAG approaches.
- latency is critically important to the use case.
- high accuracy is required to meet the customer requirement.
- you have thousands of high-quality samples with ground-truth data.
- you have clear evaluation metrics to benchmark fine-tuned models.

## Learning path to LLM Fine-Tuning



