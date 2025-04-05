# 💼 Анализ зарплат в аналитике данных и менеджменте (Москва и Санкт-Петербург)

## 📊 Описание проекта

Этот проект посвящён исследованию факторов, влияющих на уровень зарплаты в вакансиях, связанных с аналитикой данных и менеджментом. Данные собраны с hh.ru по Москве и Санкт-Петербургу на февраль 2025 года. Также проведено сравнение моделей машинного обучения для предсказания средней заработной платы.

## 🎯 Цели исследования

- Изучить структуру и распределение вакансий по ключевым характеристикам
- Проверить статистические гипотезы (t-test, χ²)
- Определить значимые признаки, влияющие на уровень зарплаты
- Построить модели машинного обучения для прогнозирования средней зарплаты (`average_salary`)

## 📂 Структура данных

Датасет содержит 551 строку и следующие переменные:

- `name` — Название вакансии  
- `area` — Город (Москва, Санкт-Петербург)  
- `employer` — Название компании  
- `salary_from`, `salary_to` — Диапазон зарплат  
- `currency` — Валюта  
- `experience` — Требуемый опыт  
- `schedule` — График работы  
- `required_skills` — Навыки, указанные в вакансии

## 🧪 Проверенные гипотезы

1. Владение инструментами анализа данных (Excel, SQL, Python, Power BI) **не влияет существенно** на зарплату аналитиков  
2. Удалённые вакансии требуют **больше опыта**  
3. Цифровые компетенции **повышают зарплаты** менеджеров

## ⚙️ Используемые библиотеки

- `pandas`, `numpy` — обработка данных  
- `scipy.stats` — статистический анализ  
- `matplotlib`, `seaborn` — визуализация  
- `scikit-learn` — `RandomForestRegressor`, `GridSearchCV`, `OneHotEncoder`  
- `lightgbm`, `xgboost` — градиентный бустинг  
- `warnings` — управление предупреждениями


## 📈 Графики и визуализация

- Распределение средней зарплаты (в том числе log-преобразованной)
- Распределение вакансий по опыту и формату работы
- Частота требуемых навыков
- Boxplot для сравнения зарплат с и без навыков

## 🔮 Перспективы

- Добавление данных об отраслях и размере компаний
- Расширение выборки (по времени и регионам)
- Анализ трендов изменения спроса на цифровые навыки

## 👩‍💻 Авторы

- Капустина Алиса 
- Потапова Дарья  
- Жданова Мария   
- Пляскина Арина    
- Михайлова Ольга  

_Проект выполнен в рамках курса ВШЭ «Управление компанией на основе данных»._
