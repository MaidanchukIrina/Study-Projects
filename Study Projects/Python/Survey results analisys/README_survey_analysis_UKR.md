
# Проект Аналізу Опитування Розробників (StackOverflow) з Використанням Pandas

Цей проект виконує аналіз результатів опитування розробників, проведеного StackOverflow, для визначення ключових характеристик респондентів, таких як досвід роботи, типи зайнятості, мови програмування та компенсація.

## Основні Цілі Проекту

1. Визначити кількість респондентів, які взяли участь у опитуванні.
2. Підрахувати, скільки респондентів відповіли на всі запитання.
3. Обчислити значення середнього, медіани та моди для досвіду роботи (WorkExp).
4. Підрахувати кількість респондентів, які працюють віддалено.
5. Визначити відсоток респондентів, які програмують на Python.
6. Підрахувати кількість респондентів, які навчались програмуванню через онлайн-курси.
7. Провести групування респондентів за країнами для обчислення середньої та медіанної компенсації серед тих, хто програмує на Python.
8. Визначити рівень освіти для 5 респондентів з найвищою компенсацією.

## Структура Проекту

### `survey_analysis.py`
Скрипт містить:
1. **Попередню обробку даних**: Завантаження даних, перевірка на пропуски.
2. **Розрахунки для центральної тенденції**: Обчислення середнього, медіани та моди для показника WorkExp.
3. **Групування за країнами та аналіз компенсації**: Середня та медіанна компенсація для Python-розробників за країнами.
4. **Аналіз рівня освіти**: Визначення рівня освіти респондентів з найбільшою компенсацією.

### `data/`
Каталог, в якому зберігаються вхідні дані опитування.

## Налаштування та Використання

1. Завантажте репозиторій та перейдіть до папки проекту.
2. Встановіть необхідні бібліотеки, якщо вони ще не встановлені:
   ```bash
   pip install pandas matplotlib
   ```
3. Запустіть скрипт:
   ```bash
   python survey_analysis.py
   ```

## Ключові Результати та Інтерпретація

- **Кількість респондентів**: 89184 осіб пройшли опитування.
- **Дистанційна робота**: Значна кількість респондентів працює віддалено.
- **Популярність Python**: Близько 48% респондентів програмують на Python.
- **Рівень освіти та компенсація**: Професійний ступінь або вища освіта часто пов'язана з вищою компенсацією.

![Графік компенсацій по країнам](images/compensation_by_country.png)

## Висновки та Рекомендації

1. **Розширення аналізу**: Провести більш детальний аналіз, додаючи додаткові метрики, як-от мінімальні та максимальні значення.
2. **Порівняння по країнам**: Оцінити інші фактори, такі як галузь або технології, які можуть впливати на компенсацію.
3. **Подальша візуалізація**: Додати більше графіків для відображення різноманітних аспектів опитування, що допоможе краще зрозуміти тенденції.

---

Цей проект надає цінні інсайти для аналізу професійних характеристик розробників та їхніх компенсацій, використовуючи бібліотеку Pandas для обробки та аналізу даних.