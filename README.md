# Fine-tuning Mistral-7B Instruct on Customer Support Data

This project demonstrates how to fine-tune the Mistral-7B Instruct model using Unsloth and LoRA PEFT (Parameter Efficient Fine-Tuning) on a real-world customer support dataset from Hugging Face.

## Project Overview

- **Model**: `mistral-7b-instruct-v0.2-bnb-4bit` (4-bit quantized via Unsloth)
- **Dataset**: Bitext Customer Support LLM Chatbot Dataset (~27K rows)
- **Format**: Instruction-Response (Alpaca-style)
- **Method**: Parameter-efficient fine-tuning using LoRA + PEFT
- **Goal**: Enhance Mistral's performance on domain-specific customer support conversations

## Requirements

### Hardware 
- GPU with at least 16GB VRAM (Tesla T4-In Google-Colab)
- CUDA-compatible environment

### Software Dependencies


## Dataset

The project uses the [Bitext Customer Support Dataset](https://huggingface.co/datasets/bitext/Bitext-customer-support-llm-chatbot-training-dataset) which contains:
- **Size**: 26,872 customer support interactions
- **Format**: CSV with instruction-response pairs
- **Categories**: Various customer support scenarios (orders, payments, shipping, etc.)
- **Quality**: Professional, human-annotated responses

## Setup and Installation

1. git clone https://github.com/Tapas000/Fine-tuning-Mistral-7B
cd mistral-7b-customer-support-finetuning

2. **Install dependencies:**

3. **Login to Hugging Face:**

