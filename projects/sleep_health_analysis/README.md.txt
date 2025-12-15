# Sleep Health and Lifestyle Analysis

## Описание проекта
Комплексный анализ факторов, влияющих на качество и продолжительность сна. EDA, визуализация, дашборды и выводы.

## Цели проекта
1. Провести exploratory data analysis (EDA) датасета о сне
2. Выявить ключевые факторы, влияющие на качество сна
3. Создать интерактивные визуализации и дашборд
4. Сформулировать практические рекомендации

## Структура проекта

sleep_health_analysis/
├── data/ # Исходные данные
|   ├──Sleep_health_and_lifestyle_dataset.csv
├── notebooks/ # Jupyter ноутбуки
├── Danko_1373_Research.ipynb
├── src/ # Исходный код
├── reports/ # Отчеты и выводы
├── visualizations/ # Сохраненные графики
│ └── sleep_analysis_dashboard.html
└── README.md # Этот файл


## Технологии
- **Язык**: Python 3.9+
- **Библиотеки**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Инструменты**: Jupyter Notebook, Git, VSCode

## Ключевые выводы
1. **Хронический недосып**: 63% участников спят менее 7 часов
2. **IT-специалисты** показывают худшее качество сна (5.2/10)
3. **Физическая активность** — самый эффективный способ улучшить сон

## Запуск проекта
```bash
# Установите зависимости
pip install -r requirements.txt

# Запустите основной ноутбук
jupyter notebook notebooks/Danko_1373_Research.ipynb