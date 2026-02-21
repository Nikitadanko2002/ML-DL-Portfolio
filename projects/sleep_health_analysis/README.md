# Sleep Health and Lifestyle Analysis

## Описание проекта
Комплексный анализ факторов, влияющих на качество и продолжительность сна. EDA, визуализация, дашборды и выводы.

## Цели проекта
1. Провести exploratory data analysis (EDA) датасета о сне
2. Выявить ключевые факторы, влияющие на качество сна
3. Создать интерактивные визуализации и дашборд
4. Сформулировать практические рекомендации

## Структура проекта

| Путь | Тип | Назначение |
|------|-----|------------|
| `data/` | Папка | Исходные данные |
| `data/Sleep_health_and_lifestyle_dataset.csv` | Файл | Основной датасет с данными о сне |
| `notebooks/` | Папка | Jupyter ноутбуки с анализом |
| `notebooks/Danko_1373_Research.ipynb` | Файл | Основной ноутбук с полным анализом |
| `src/` | Папка | Исходный код Python |
| `reports/` | Папка | Отчеты и выводы |
| `visualizations/` | Папка | Сохраненные графики и дашборды |
| `visualizations/sleep_analysis_dashboard.html` | Файл | Интерактивный дашборд Plotly |
| `README.md` | Файл | Этот файл с документацией |

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
# Клонировать репозиторий
git clone https://github.com/Nikitadanko2002/ML-DL-Portfolio.git

# Перейти в папку проекта
cd ML-DL-Portfolio/projects/sleep_health_analysis

# Установите зависимости
pip install -r requirements.txt

# Запустите основной ноутбук
jupyter notebook notebooks/Danko_1373_Research.ipynb
