# Бесплатные поставщики больших языковых моделей

Этот репозиторий содержит список бесплатных поставщиков больших языковых моделей (LLM).

## Список поставщиков и моделей

### OpenRouter

| Модель | Размер | Контекст | Токены ввода | Токены вывода | Ограничения |
|--------|--------|----------|---------------|----------------|-------------|
| Nous: Hermes 3 405B Instruct | 405B | 131K | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| Meta: Llama 3.1 8B Instruct (free) | 8B | 131,072 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| Google: Gemma 2 9B (free) | 9B | 8,192 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| Mistral: Mistral 7B Instruct (free) | 7.3B | 32,768 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |
| OpenChat 3.5 7B (free) | 7B | 8,192 | $0/M | $0/M | 20 запросов/мин, 200 запросов/день |

### [HuggingChat FastAPI](https://github.com/Lorodn4x/huggingchat-fastapi) (неофициальный)

| Модель | Описание |
|--------|----------|
| meta-llama/Meta-Llama-3.1-70B-Instruct | Идеально подходит для повседневного использования. Быстрая и чрезвычайно способная модель, соответствующая возможностям закрытых моделей. |
| CohereForAI/c4ai-command-r-plus | Крупнейшая языковая модель Cohere, оптимизированная для разговорного взаимодействия и использования инструментов. |
| mistralai/Mixtral-8x7B-Instruct-v0.1 | Высококачественная разреженная модель смеси экспертов с открытыми весами. |
| NousResearch/Nous-Hermes-2-Mixtral-8x7B-DPO | Сильная флагманская модель Nous Hermes, обученная на Mixtral 8x7B. |
| 01-ai/Yi-1.5-34B-Chat | Сильная производительность в рассуждениях при сохранении отличных возможностей в понимании языка. |
| mistralai/Mistral-7B-Instruct-v0.3 | Небольшая модель с хорошими возможностями в понимании языка и здравом смысле. |
| microsoft/Phi-3-mini-4k-instruct | Одна из лучших малых моделей (3.8B параметров), супер быстрая для простых задач. |

### [Groq](https://console.groq.com/) (быстрый вывод)

Groq предоставляет доступ к различным моделям с высокой скоростью вывода.

#### Доступные модели

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

#### Модели для распознавания речи

| Модель | Разработчик | Макс. размер файла | Ограничения (запросы/мин, запросы/день, аудио сек/час, аудио сек/день) |
|--------|-------------|---------------------|------------------------------------------------------------------------|
| Distil-Whisper English | HuggingFace | 25 MB | 20, 2,000, 7,200, 28,800 |
| Whisper | OpenAI | 25 MB | 20, 2,000, 7,200, 28,800 |

Примечание: Ограничения могут меняться. Рекомендуется проверять актуальную информацию на официальном сайте Groq.

## Примечания

1. Модели OpenRouter доступны с бесплатным ограниченным доступом.
2. Ограничения по количеству запросов в минуту и в день применяются ко всем бесплатным моделям на OpenRouter.
3. Для моделей OpenRouter указана стоимость $0/M для токенов ввода и вывода в рамках бесплатного доступа.
4. Размер контекста и параметры моделей могут варьироваться.
5. Дополнительные ограничения могут применяться в зависимости от количества доступных кредитов на аккаунте пользователя.
6. HuggingChat FastAPI и gpt4free - неофициальные проекты и поставщики. Ограничения и доступность могут часто меняться.
7. Groq предоставляет быстрый вывод для различных моделей, но имеет ограничения на использование.

## Как использовать

Для каждого провайдера предоставлена краткая информация о доступных моделях и ограничениях. Для получения более подробной информации рекомендуется обратиться к документации соответствующего проекта или провайдера.

## Вклад

Если вы знаете о других бесплатных поставщиках LLM или моделях, пожалуйста, создайте issue или отправьте pull request для обновления информации.
