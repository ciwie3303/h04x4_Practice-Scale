# Приложение для анализа текста ИИ и перефразирования

## Обзор

Это приложение на Streamlit позволяет пользователям анализировать текст на наличие следов ИИ и перефразировать его для улучшения SEO. Приложение использует DistilBERT для обнаружения ИИ в тексте и предлагает несколько методов перефразирования текста, включая модели Gemma, Llama и цепи Маркова.

## Возможности

- **Анализ ИИ:** Анализ текста для определения, был ли он написан человеком или ИИ.
- **Перефразирование текста:** Перефразирование текста с использованием различных моделей для улучшения SEO/Текста.
- **Удобный интерфейс:** Простой и интуитивно понятный интерфейс, построенный на Streamlit.

## Установка

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/h04x4_Practice-Scale
    ```

2. Перейдите в директорию проекта:
    ```bash
    cd h04x4_Practice-Scale
    ```

3. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

4. Запустите приложение:
    ```bash
    streamlit run app.py
    ```

## Использование

### Анализ текста на наличие следов ИИ

1. Перейдите на вкладку "Анализ следов ИИ".
2. Введите текст, который хотите проанализировать.
3. Нажмите кнопку "Анализировать".
4. Результаты анализа будут отображены на экране.

### Перефразирование текста

1. Перейдите на вкладку "Переформулирование текста".
2. Введите текст, который хотите перефразировать.
3. Выберите метод перефразирования.
4. Нажмите кнопку "Переформулировать".
5. Перефразированный текст будет отображен на экране.

## Требования

- Установить https://ollama.com/download/windows 
 - ollama run llama3:70 (40гб)
 - ollama run gemma (5-6гб)
 - ollama run qwen2 (5гб)
- Python 3.11
- Streamlit
- Googletrans
- transformers
- torch
- Дополнительные зависимости указаны в `requirements.txt`


