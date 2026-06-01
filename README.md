# A/B-тест: анализ результатов

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/katpvlv/ab-test-analysis/blob/main/AB_test.ipynb)

**👉 [Открыть ноутбук в Google Colab](https://colab.research.google.com/github/katpvlv/ab-test-analysis/blob/main/AB_test.ipynb)** — посмотреть анализ онлайн без установки Jupyter

Тестовое задание на позицию Data Analyst.
Период теста: 01.01.2025 – 28.02.2025.

## Подход
Гибридное решение: расчёт метрик и data quality на SQL (PostgreSQL),
кросс-проверка и статистические тесты на Python (pandas, numpy, scipy, matplotlib).

## Структура
- `AB_test.ipynb` — основной анализ с кодом и выводами
- `AB_test.html` — статичная версия ноутбука для быстрого просмотра в браузере

Исходные данные (`ab_test_data.csv`) не включены в репозиторий,
были предоставлены в рамках тестового задания.

## Стек
Python: pandas, numpy, scipy, matplotlib
SQL: PostgreSQL (DBeaver)

## Главный результат
Изменение в группе B значимо улучшило доход (ARPU +9.2%, p < 0.001)
и вовлечённость (time played +9.4%, sessions +6.8%) за счёт роста
среднего чека среди платящих (ARPPU +10.9%). Конверсия не изменилась.

**Рекомендация:** внедрять на 100% аудитории.

## Как воспроизвести
1. Установить зависимости: `pip install pandas numpy scipy matplotlib`
2. Положить `ab_test_data.csv` в папку с ноутбуком
3. Открыть ноутбук в Jupyter, запустить ячейки сверху вниз
