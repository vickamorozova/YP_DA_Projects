# Анализ пользовательского поведения в мобильном приложении

**Задачи исследования**

На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования.

**Ход исследования**

Исследование пройдёт в несколько этапов:

1) Обзор и предобработка данных.

2) Анализ данных.

3) Анализ воронки событий.

4) Интерпретация результатов А/А/В эксперимента.

В данном проекте мною были изучены принципы событийной аналитики. Я построила воронку продаж, исследовала путь пользователей до покупки. Проанализировала результаты A/B-теста введения новых шрифтов. Сравнила 2 контрольных группы между
собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой.

Используемые библиотеки -  `pandas`, `scipy`, `numpy`, `matplotlib`, `math`, `plotly`.

**Результат исследования**

Эксперимент показал, что изменение шрифта не показало статистически значимого различия в показателях конверсии у группы с измененённым шрифтом и контрольной группы.

Самое узкое место в воронке продаж переход из главноого экрана в каталог продуктов, таким образом необходимо продумать мероприятия по увеличению конверсии на данном этапе.

**Статус исследования**

Исследование завершено.
