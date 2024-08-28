 # Free Large Language Model (LLM) Providers

This repository contains a list of free Large Language Model (LLM) providers and information about available models.

[Русская версия (Russian version)](README.md)

## Table of Contents

1. [OpenRouter](#openrouter)
2. [HuggingChat FastAPI](#huggingchat-fastapi-unofficial)
3. [gpt4free](#gpt4free-unofficial-unstable)
4. [Groq](#groq-fast-inference)
5. [General Notes](#general-notes)
6. [How to Use](#how-to-use)
7. [Contribution](#contribution)

## OpenRouter

[OpenRouter](https://openrouter.ai/) provides access to various models with free limited access.

| Model | Size | Context | Input Tokens | Output Tokens | Limitations |
|-------|------|---------|--------------|----------------|-------------|
| Nous: Hermes 3 405B Instruct | 405B | 131K | $0/M | $0/M | 20 requests/min, unlimited per day* |
| Meta: Llama 3.1 8B Instruct (free) | 8B | 131,072 | $0/M | $0/M | 20 requests/min, 200 requests/day |
| Google: Gemma 2 9B (free) | 9B | 8,192 | $0/M | $0/M | 20 requests/min, 200 requests/day |
| Mistral: Mistral 7B Instruct (free) | 7.3B | 32,768 | $0/M | $0/M | 20 requests/min, 200 requests/day |
| OpenChat 3.5 7B (free) | 7B | 8,192 | $0/M | $0/M | 20 requests/min, 200 requests/day |

*Note: Unlimited requests per day for Nous: Hermes 3 405B Instruct is a temporary promotion. This model will become paid in the future.

## HuggingChat FastAPI (unofficial)

[HuggingChat FastAPI](https://github.com/Lorodn4x/huggingchat-fastapi) is an unofficial project providing access to HuggingFace models.

| Model | Description |
|-------|-------------|
| meta-llama/Meta-Llama-3.1-70B-Instruct | Fast and powerful model for everyday use |
| CohereForAI/c4ai-command-r-plus | Cohere's largest model for conversational interaction |
| mistralai/Mixtral-8x7B-Instruct-v0.1 | High-quality sparse mixture of experts model |
| NousResearch/Nous-Hermes-2-Mixtral-8x7B-DPO | Strong Nous Hermes model based on Mixtral 8x7B |
| 01-ai/Yi-1.5-34B-Chat | Model with strong reasoning and language understanding capabilities |
| mistralai/Mistral-7B-Instruct-v0.3 | Compact model with good language understanding |
| microsoft/Phi-3-mini-4k-instruct | Fast small model (3.8B parameters) for simple tasks |

## gpt4free (unofficial, unstable)

[gpt4free](https://github.com/xtekky/gpt4free) is an unofficial provider that offers access to various models through different providers. The project is unstable and may change frequently.

| Features | Description |
|----------|-------------|
| Graphical Interface | Has a built-in web interface for convenient use |
| API | Provides API for integration with other applications |
| Multiple Providers | Supports various providers and models |

### Available Models

| Model | Base Provider | Number of Providers |
|-------|---------------|---------------------|
| gpt-3.5-turbo | OpenAI | 8+ |
| gpt-4 | OpenAI | 2+ |
| gpt-4-turbo | OpenAI | 1 (Bing) |
| Llama-2 (7b/13b/70b) | Meta | 2-3+ |
| Meta-Llama-3 (8b/70b) | Meta | 1-2+ |
| CodeLlama (34b/70b) | Meta | 1-2 |
| Mixtral-8x7B-Instruct-v0.1 | Huggingface | 4+ |
| Mistral-7B-Instruct (v0.1/v0.2) | Huggingface | 3+ |
| gemini/gemini-pro | Google | 1-2+ |
| claude-v2 | Anthropic | 1+ |
| claude-3 (opus/sonnet) | Anthropic | 1 (You) |

### Image and Vision Models

| Provider | Image Model | Vision Model |
|----------|-------------|--------------|
| Bing | dall-e-3 | gpt-4-vision |
| DeepInfra | stability-ai/sdxl | llava-1.5-7b-hf |
| Gemini | ✔️ | ✔️ |
| GeminiPro | ❌ | gemini-1.5-pro |
| MetaAI | ✔️ | ❌ |
| OpenaiChat | dall-e-3 | gpt-4-vision |
| Reka | ❌ | ✔️ |
| Replicate | stability-ai/sdxl | llava-v1.6-34b |
| You | dall-e-3 | ✔️ |

## Groq (fast inference)

[Groq](https://console.groq.com/) offers high-speed access to various models.

### Text Models

| Model | Developer | Context | Limitations (requests/min, requests/day, tokens/min) |
|-------|-----------|---------|-----------------------------------------------------|
| Gemma 2 9B | Google | 8,192 | 30, 14,400, 15,000 |
| Gemma 7B | Google | 8,192 | 30, 14,400, 15,000 |
| Llama 3 Groq 70B Tool Use (Preview) | Groq | 8,192 | 30, 14,400, 15,000 |
| Llama 3 Groq 8B Tool Use (Preview) | Groq | 8,192 | 30, 14,400, 15,000 |
| Llama 3.1 70B (Preview) | Meta | 131,072 | 100, 14,400, 131,072 |
| Llama 3.1 8B (Preview) | Meta | 131,072 | 30, 14,400, 131,072 |
| Llama Guard 3 8B | Meta | 8,192 | 30, 14,400, 15,000 |
| Meta Llama 3 70B | Meta | 8,192 | 30, 14,400, 6,000 |
| Meta Llama 3 8B | Meta | 8,192 | 30, 14,400, 30,000 |
| Mixtral 8x7B | Mistral | 32,768 | 30, 14,400, 5,000 |

### Speech Recognition Models

| Model | Developer | Max File Size | Limitations (requests/min, requests/day, audio sec/hour, audio sec/day) |
|-------|-----------|---------------|------------------------------------------------------------------------|
| Distil-Whisper English | HuggingFace | 25 MB | 20, 2,000, 7,200, 28,800 |
| Whisper | OpenAI | 25 MB | 20, 2,000, 7,200, 28,800 |

## General Notes

- All presented models have usage limitations.
- Model parameters and limitations may change over time.
- Unofficial projects (HuggingChat FastAPI, gpt4free) may have unstable availability.
- It is recommended to check the current information on the official provider websites.

## How to Use

Brief information about available models and limitations is provided for each provider. For more detailed information and usage instructions, please refer to the documentation of the respective project or provider.

## Contribution

If you know of other free LLM providers or models, please create an issue or submit a pull request to update the information. Your contribution will help keep this resource up-to-date and useful for the community.
