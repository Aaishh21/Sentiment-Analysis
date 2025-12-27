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

1. Клонируйте репозиторий: <br>
git clone <https://github.com/Aaishh21/Sentiment-Analysis.git> <br>
cd sentiment-analysis

2. Установите зависимости:<br>
pip install -r requirements.txt

3. Запустите Jupiter Notebook:<br>
jupyter notebook sentiment_analysis.ipynb

---

## Датасет

Используется датасет Restaurant Reviews с Kaggle. <br>
[Ссылка на Kaggle](https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews?resource=download)

---

## Пример работы модели
"The food was really good" → Positive ^_^ <br>
"The service was terrible." → Negative T_T