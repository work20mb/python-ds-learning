# 🐍 План обучения Python для Data Science

**Уровень:** Полный новичок  
**Темп обучения:** 1-2 часа в день  
**Длительность:** 12 недель  
**Цель:** Освоить Python и начать работать с данными

---

## 📊 Структура курса

### **Блок 1: Основы Python (Недели 1-4)**
Фундамент для всех остальных знаний

- **Неделя 1:** Синтаксис, переменные, типы данных
- **Неделя 2:** Условия, циклы, функции
- **Неделя 3:** Списки, кортежи, словари
- **Неделя 4:** Работа с файлами, обработка ошибок

### **Блок 2: Библиотеки для анализа данных (Недели 5-8)**
NumPy, Pandas, визуализация

- **Неделя 5:** NumPy - работа с массивами
- **Неделя 6:** Pandas - работа с DataFrames
- **Неделя 7:** Очистка и трансформация данных
- **Неделя 8:** Matplotlib и Seaborn - визуализация

### **Блок 3: Анализ данных и ML (Недели 9-12)**
Статистика и машинное обучение

- **Неделя 9:** Основы статистики
- **Неделя 10:** Exploratory Data Analysis (EDA)
- **Неделя 11:** Введение в Scikit-learn
- **Неделя 12:** Финальный проект

---

## 🎯 Цели по неделям

### **НЕДЕЛЯ 1: Знакомство с Python**
**Цель:** Установить Python, написать первые программы

#### Темы:
- Установка Python и IDE (VS Code или PyCharm)
- Переменные и типы данных (int, float, str, bool)
- Базовые операции (арифметика, конкатенация)
- Функция `print()` и `input()`

#### Практика:
- [ ] Написать программу для простых вычислений
- [ ] Создать калькулятор (+, -, *, /)
- [ ] Программа "Угадай число"

#### Ресурсы:
- 📚 [Python для начинающих - официальная документация](https://docs.python.org/3/tutorial/introduction.html)
- 🎥 [Freecodecamp Python Tutorial (0-4 часа)](https://www.youtube.com/watch?v=rfscVS0vtik)

---

### **НЕДЕЛЯ 2: Управление потоком выполнения**
**Цель:** Написать программы с логикой

#### Темы:
- Условные операторы (if, elif, else)
- Логические операторы (and, or, not)
- Циклы (for, while)
- Break и continue

#### Практика:
- [ ] Программа проверки простого числа
- [ ] Таблица умножения
- [ ] Генератор чисел Фибоначчи

#### Ресурсы:
- 📚 [Control Flow в Python](https://docs.python.org/3/tutorial/controlflow.html)

---

### **НЕДЕЛЯ 3: Функции и структуры данных**
**Цель:** Написать переиспользуемый код

#### Темы:
- Функции (def, параметры, возвращаемые значения)
- Списки (создание, индексация, методы)
- Кортежи и неизменяемость
- Словари (создание, доступ, методы)

#### Практика:
- [ ] Функция для расчета факториала
- [ ] Работа со списком студентов и оценок
- [ ] Создать словарь контактов

#### Ресурсы:
- 📚 [Функции в Python](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
- 📚 [Структуры данных](https://docs.python.org/3/tutorial/datastructures.html)

---

### **НЕДЕЛЯ 4: Файлы и обработка ошибок**
**Цель:** Работать с реальными данными

#### Темы:
- Открытие и закрытие файлов (with statement)
- Чтение и запись в файлы
- CSV формат
- Try-except блоки
- Типы исключений

#### Практика:
- [ ] Прочитать и вывести содержимое файла
- [ ] Записать данные в CSV
- [ ] Создать программу с обработкой ошибок

#### Ресурсы:
- 📚 [Работа с файлами](https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files)
- 📚 [Исключения](https://docs.python.org/3/tutorial/errors.html)

---

### **НЕДЕЛЯ 5: NumPy - работа с массивами**
**Цель:** Освоить числовые вычисления

#### Темы:
- Установка NumPy (`pip install numpy`)
- Создание массивов (array, zeros, ones, arange)
- Индексация и срезы массивов
- Математические операции
- Форма и переформирование массивов (reshape)
- Базовая статистика (mean, std, min, max)

#### Практика:
- [ ] Создать массив и выполнить операции
- [ ] Матричные вычисления
- [ ] Анализ статистики массива

#### Ресурсы:
- 📚 [NumPy Documentation](https://numpy.org/doc/stable/)
- 🎥 [NumPy Tutorial for Beginners](https://www.youtube.com/watch?v=QUT1VHiUKWQ)

---

### **НЕДЕЛЯ 6: Pandas - работа с данными**
**Цель:** Анализировать табличные данные

#### Темы:
- Установка Pandas (`pip install pandas`)
- Series и DataFrame
- Загрузка данных (CSV, Excel)
- Базовое исследование (head, info, describe)
- Индексация и фильтрация данных
- Выбор столбцов и строк (loc, iloc)

#### Практика:
- [ ] Загрузить CSV файл и исследовать
- [ ] Отфильтровать данные по условиям
- [ ] Выбрать нужные столбцы

#### Ресурсы:
- 📚 [Pandas Documentation](https://pandas.pydata.org/docs/)
- 🎥 [Pandas Tutorial](https://www.youtube.com/watch?v=dcqPhpY7tWk)

---

### **НЕДЕЛЯ 7: Очистка и трансформация данных**
**Цель:** Подготовить данные для анализа

#### Темы:
- Пропущенные значения (NaN, dropna, fillna)
- Дубликаты (drop_duplicates)
- Переименование столбцов
- Типы данных (astype, convert_dtypes)
- Группировка данных (groupby)
- Агрегация (sum, count, mean)

#### Практика:
- [ ] Очистить датасет от пропусков
- [ ] Найти и удалить дубликаты
- [ ] Сгруппировать данные и посчитать статистику

#### Ресурсы:
- 📚 [Data Cleaning in Pandas](https://pandas.pydata.org/docs/user_guide/missing_data.html)

---

### **НЕДЕЛЯ 8: Визуализация данных**
**Цель:** Визуально представить данные

#### Темы:
- Matplotlib - основы
- Типы графиков (line, bar, scatter, histogram)
- Seaborn - красивые графики
- Customization (цвета, метки, легенды)
- Сохранение графиков

#### Практика:
- [ ] Создать линейный график
- [ ] Столбчатая диаграмма
- [ ] Scatter plot и histogram
- [ ] Красивый график с Seaborn

#### Ресурсы:
- 📚 [Matplotlib Tutorial](https://matplotlib.org/stable/tutorials/index.html)
- 📚 [Seaborn Documentation](https://seaborn.pydata.org/)

---

### **НЕДЕЛЯ 9: Основы статистики**
**Цель:** Понять статистические концепции

#### Темы:
- Описательная статистика (mean, median, mode, std)
- Распределения (normal, binomial)
- Корреляция и ковариация
- Гипотезы и p-value
- Нормализация данных

#### Практика:
- [ ] Рассчитать статистику датасета
- [ ] Найти корреляцию между переменными
- [ ] Нормализовать данные

#### Ресурсы:
- 📚 [SciPy Statistics](https://docs.scipy.org/doc/scipy/reference/stats.html)
- 🎥 [Statistics Fundamentals](https://www.youtube.com/watch?v=xxpc-HPKN28)

---

### **НЕДЕЛЯ 10: Exploratory Data Analysis (EDA)**
**Цель:** Исследовать данные перед моделированием

#### Темы:
- Автоматический EDA
- Обнаружение выбросов (outliers)
- Анализ распределений
- Relationships между переменными
- Feature engineering (создание новых признаков)

#### Практика:
- [ ] Провести полный EDA реального датасета
- [ ] Создать отчет с визуализацией
- [ ] Найти и обработать выбросы

#### Ресурсы:
- 📚 [EDA Guide](https://en.wikipedia.org/wiki/Exploratory_data_analysis)

---

### **НЕДЕЛЯ 11: Введение в Scikit-learn**
**Цель:** Построить первую модель машинного обучения

#### Темы:
- Установка Scikit-learn
- Разделение данных (train_test_split)
- Линейная регрессия
- Классификация (логистическая регрессия)
- Оценка моделей (accuracy, precision, recall, F1)
- Cross-validation

#### Практика:
- [ ] Построить модель линейной регрессии
- [ ] Классификатор для бинарной задачи
- [ ] Оценить качество модели

#### Ресурсы:
- 📚 [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- 🎥 [Scikit-learn Tutorial](https://www.youtube.com/watch?v=0B5eIkxVfAI)

---

### **НЕДЕЛЯ 12: Финальный проект**
**Цель:** Применить все полученные знания

#### Проект: Анализ и предсказание на реальных данных

**Этапы:**
1. Выбрать датасет (Kaggle, UCI Machine Learning Repository)
2. Провести EDA и визуализацию
3. Очистить и подготовить данные
4. Построить несколько моделей
5. Оценить и сравнить результаты
6. Создать отчет с выводами

#### Рекомендуемые датасеты:
- 🎯 [Titanic Dataset](https://www.kaggle.com/c/titanic) - классификация
- 🎯 [Housing Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) - регрессия
- 🎯 [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris) - классификация

---

## 📚 Рекомендуемые ресурсы

### Обучение:
- 🎓 [Codecademy - Python Course](https://www.codecademy.com/learn/learn-python-3)
- 🎓 [DataCamp - Data Science Track](https://www.datacamp.com/)
- 🎓 [Kaggle Learn - Micro Courses](https://www.kaggle.com/learn)
- 📖 [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)

### Практика:
- 💻 [LeetCode](https://leetcode.com/) - алгоритмические задачи
- 💻 [HackerRank](https://www.hackerrank.com/) - практические задания
- 💻 [Kaggle](https://www.kaggle.com/) - реальные датасеты и конкурсы

### Документация:
- 📚 [Python Official Docs](https://docs.python.org/3/)
- 📚 [NumPy Docs](https://numpy.org/doc/)
- 📚 [Pandas Docs](https://pandas.pydata.org/docs/)
- 📚 [Scikit-learn Docs](https://scikit-learn.org/)

---

## 🎯 Как пользоваться этим курсом

1. **Каждую неделю:**
   - Изучите теоретический материал (30-60 минут)
   - Выполните практические задания (60-90 минут)
   - Создайте файл с кодом в папке `/week-X/`

2. **Отслеживание прогресса:**
   - Чекбоксы в этом README
   - GitHub Issues для каждой недели
   - Commits с вашим кодом

3. **Если застрянете:**
   - Переносите задачу на следующий день
   - Используйте Stack Overflow или ChatGPT
   - Пересмотрите материал еще раз

---

## 📁 Структура репозитория

```
python-ds-learning/
├── README.md (этот файл)
├── week-1/
│   ├── notes.md
│   └── exercises.py
├── week-2/
│   ├── notes.md
│   └── exercises.py
├── ...
├── week-12/
│   ├── final_project.py
│   └── analysis_report.md
└── resources/
    ├── datasets/
    └── cheatsheets/
```

---

## ✅ Чеклист для начала

- [ ] Установить Python 3.10+
- [ ] Установить IDE (VS Code или PyCharm)
- [ ] Создать виртуальное окружение
- [ ] Установить необходимые библиотеки
- [ ] Создать первый файл `hello_world.py`
- [ ] Начать неделю 1!

---

## 🚀 Готовы начать?

**Начните с [Недели 1](./week-1/)** и удачи в обучении! 🐍

---

**Последнее обновление:** Сентябрь 2026  
**Ваш план:** 12 недель, 1-2 часа в день  
**Финальная цель:** Уверенное использование Python для Data Science!
