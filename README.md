# Marketing Response Prediction

Проект по построению модели, предсказывающей вероятность покупки клиентом интернет-магазина в течение 90 дней после рассылки.

## Состав репозитория
- `Marketing.ipynb` — ноутбук с подготовкой данных, обучением и оценкой моделей.  
- `requirements.txt` — список зависимостей.  
- `README.md` — описание проекта.  

## Как запустить
1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/<USERNAME>/marketing-response.git
   cd marketing-response


Установить зависимости:

pip install -r requirements.txt

Открыть ноутбук:

jupyter notebook Marketing.ipynb

Результат

Лучшая модель — логистическая регрессия.

Метрика ROC-AUC на тестовой выборке: 0.7087.