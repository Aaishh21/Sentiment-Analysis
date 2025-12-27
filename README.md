# Sentiment Analysis of Restaurant Reviews

Определяет, является ли отзыв о ресторане положительным или отрицательным.  

Используемые технологии: Python, pandas, scikit-learn, NLTK, Matplotlib, Seaborn.

---

## Описание проекта

- Загрузка и очистка текста отзывов
- Преобразование текста в числовой формат (Bag of Words)
- Обучение модели Naive Bayes
- Оценка точности модели и визуализация результатов
- Функция для предсказания нового отзыва

---

## Установка и запуск

1. Клонируйте репозиторий:
git clone <URL_репозитория>
cd sentiment-analysis

2. Установите зависимости:
pip install -r requirements.txt

3. Запустите Jupiter Notebook:
jupyter notebook sentiment_analysis.ipynb

---

## Датасет

Используется датасет Restaurant Reviews с Kaggle:
[Ссылка на Kaggle](https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews?resource=download)

---

## Пример работы модели
"The food was amazing and the service was great!" → Positive ^_^
"The service was terrible and the food was cold." → Negative T_T