# Прогнозирование расходов на медицинскую страховку + Статистический анализ

---

## Описание проекта

Проект посвящён прогнозированию расходов на медицинскую страховку на основе характеристик клиентов: возраста, пола, индекса массы тела (BMI), наличия детей, факта курения и региона проживания.

В проекте объединены исследовательский анализ данных (EDA), проверка статистических гипотез и построение моделей машинного обучения.

---

## Структура проекта

1. Загрузка и первичная проверка данных.
2. Анализ данных (EDA).
3. Категоризация индекса массы тела (BMI) по американским стандартам.
4. Проверка статистической гипотезы.
5. Подготовка данных для ML.
6. Проверка мультиколлинеарности признаков (VIF)
7. Построение и сравнение моделей.
8. Оптимизация лучшей модели.
9. Финальные выводы и рекомендации.
---

## Результаты

- Построенная модель градиентного бустинга объясняет около 88% вариации расходов (Test R² ≈ 0.878).
- Средняя ошибка предсказания модели составляет около 2491 у.е.
- Факт курения статистически значимо увеличивает стоимость медицинской страховки.
- Индекс массы тела также влияет на расходы, особенно в категориях ожирения.

---

## Выводы

Разработанная модель может быть использована для предварительной оценки расходов клиентов при расчёте страховых тарифов. Рекомендуется дополнительно учитывать здоровье клиента (курение, вес) в тарифной политике страховой компании.

---
