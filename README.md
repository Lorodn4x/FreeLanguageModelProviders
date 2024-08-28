# Бесплатные поставщики больших языковых моделей (LLM)

Этот репозиторий содержит список бесплатных поставщиков больших языковых моделей (LLM) и информацию о доступных моделях.

[English version (Английская версия)](README_EN.md)

## Содержание

1. [OpenRouter](#openrouter)
2. [HuggingChat FastAPI](#huggingchat-fastapi-неофициальный)
3. [gpt4free](#gpt4free-неофициальный-нестабильный)
4. [Groq](#groq-быстрый-вывод)
5. [Общие примечания](#общие-примечания)
6. [Как использовать](#как-использовать)
7. [Вклад](#вклад)

## OpenRouter

[OpenRouter](https://openrouter.ai/) предоставляет доступ к различным моделям с бесплатным ограниченным доступом.

| Модель | Размер | Контекст | Токены ввода | Токены вывода | Ограничения |
|--------|--------|----------|---------------|----------------|-------------|
| Nous: Hermes 3 405B Instruct | 405B | 131K | $0/M | $0/M | 20 запросов/мин, неограниченно в день* |
| Meta: Llama 3.1 8B Instruct (free) | 8B | 131,072 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| Google: Gemma 2 9B (free) | 9B | 8,192 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| Mistral: Mistral 7B Instruct (free) | 7.3B | 32,768 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| OpenChat 3.5 7B (free) | 7B | 8,192 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |

*Примечание: Неограниченное количество запросов в день для Nous: Hermes 3 405B Instruct является временной акцией. В будущем эта модель станет платной.

## HuggingChat FastAPI (неофициальный)

[HuggingChat FastAPI](https://github.com/Lorodn4x/huggingchat-fastapi) - неофициальный проект, предоставляющий доступ к моделям HuggingFace.

| Модель | Описание |
|--------|----------|
| meta-llama/Meta-Llama-3.1-70B-Instruct | Быстрая и мощная модель для повседневного использования |
| CohereForAI/c4ai-command-r-plus | Крупнейшая модель Cohere для разговорного взаимодействия |
| mistralai/Mixtral-8x7B-Instruct-v0.1 | Высококачественная разреженная модель смеси экспертов |
| NousResearch/Nous-Hermes-2-Mixtral-8x7B-DPO | Сильная модель Nous Hermes на базе Mixtral 8x7B |
| 01-ai/Yi-1.5-34B-Chat | Модель с сильными возможностями рассуждения и понимания языка |
| mistralai/Mistral-7B-Instruct-v0.3 | Компактная модель с хорошим пониманием языка |
| microsoft/Phi-3-mini-4k-instruct | Быстрая малая модель (3.8B параметров) для простых задач |

## gpt4free (неофициальный, нестабильный)

[gpt4free](https://github.com/xtekky/gpt4free) - это неофициальный поставщик, который предоставляет доступ к различным моделям через разные провайдеры. Проект нестабилен и может часто меняться.

| Особенности | Описание |
|-------------|----------|
| Графический интерфейс | Имеет встроенный веб-интерфейс для удобного использования |
| API | Предоставляет API для интеграции с другими приложениями |
| Множество провайдеров | Поддерживает различные провайдеры и модели |

### Доступные модели

| Модель | Базовый провайдер | Количество провайдеров |
|--------|-------------------|------------------------|
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

### Модели для работы с изображениями и зрением

| Провайдер | Модель изображений | Модель зрения |
|-----------|---------------------|----------------|
| Bing | dall-e-3 | gpt-4-vision |
| DeepInfra | stability-ai/sdxl | llava-1.5-7b-hf |
| Gemini | ✔️ | ✔️ |
| GeminiPro | ❌ | gemini-1.5-pro |
| MetaAI | ✔️ | ❌ |
| OpenaiChat | dall-e-3 | gpt-4-vision |
| Reka | ❌ | ✔️ |
| Replicate | stability-ai/sdxl | llava-v1.6-34b |
| You | dall-e-3 | ✔️ |

## Groq (быстрый вывод)

[Groq](https://console.groq.com/) предлагает высокоскоростной доступ к различным моделям.

### Текстовые модели

| Модель | Разработчик | Контекст | Ограничения (запросы/мин, запросы/день, токены/мин) |
|--------|-------------|----------|-----------------------------------------------------|
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

### Модели для распознавания речи

| Модель | Разработчик | Макс. размер файла | Ограничения (запросы/мин, запросы/день, аудио сек/час, аудио сек/день) |
|--------|-------------|---------------------|------------------------------------------------------------------------|
| Distil-Whisper English | HuggingFace | 25 MB | 20, 2,000, 7,200, 28,800 |
| Whisper | OpenAI | 25 MB | 20, 2,000, 7,200, 28,800 |

## Общие примечания

- Все представленные модели имеют ограничения на использование.
- Параметры моделей и ограничения могут меняться со временем.
- Неофициальные проекты (HuggingChat FastAPI, gpt4free) могут иметь нестабильную доступность.
- Рекомендуется проверять актуальную информацию на официальных сайтах провайдеров.

## Как использовать

Для каждого провайдера предоставлена краткая информация о доступных моделях и ограничениях. Для получения более подробной информации и инструкций по использованию обратитесь к документации соответствующего проекта или провайдера.

## Вклад

Если вы знаете о других бесплатных поставщиках LLM или моделях, пожалуйста, создайте issue или отправьте pull request для обновления информации. Ваш вклад поможет поддерживать этот ресурс актуальным и полезным для сообщества.
