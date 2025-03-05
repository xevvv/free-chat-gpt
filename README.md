# FreeGPTs

FreeGPTs is a Python library that provides free access to powerful AI models, including **ChatGPT-4**, **GPT-4o-mini**, and **SearchGPT**, for seamless integration into your Python applications. With this library, you can quickly and easily interact with these models to answer questions, generate text, and perform search-based tasks.

## Installation

You can install the library directly from PyPI using pip:

```bash
pip install freegpts
```

## Example Usage

```python
from freegpts import gpt4, gpt4omini, searchgpt

# Ask the user for a question
question = input("Enter question: ")

# Get answers from different models
print("Answer from GPT-4:")
print(gpt4.answer(question))

print("Answer from GPT-4o-mini:")
print(gpt4omini.answer(question))

print("Answer from SearchGPT:")
print(searchgpt.answer(question))
```

## Expanding Neural Networks
The library will continue to grow over time, with new AI models being added regularly to provide even more capabilities and functionality.

***

# FreeGPTs

FreeGPTs — это библиотека Python, которая предоставляет бесплатный доступ к мощным моделям ИИ, включая ChatGPT-4, GPT-4o-mini и SearchGPT, для интеграции в ваши Python-приложения. С помощью этой библиотеки вы можете быстро и легко взаимодействовать с этими моделями для ответа на вопросы, генерации текста и выполнения поисковых задач.

## Установка

Вы можете установить библиотеку напрямую из PyPI с помощью pip:

```bash
pip install freegpts
```

## Пример использования

```python
from freegpts import gpt4, gpt4omini, searchgpt

# Запросить у пользователя вопрос
question = input("Введите вопрос: ")

# Получить ответы от разных моделей
print("Ответ от GPT-4:")
print(gpt4.answer(question))

print("Ответ от GPT-4o-mini:")
print(gpt4omini.answer(question))

print("Ответ от SearchGPT:")
print(searchgpt.answer(question))
```

## Расширение нейросетей
Библиотека будет продолжать развиваться с добавлением новых моделей ИИ, чтобы предоставить еще больше возможностей и функционала.
