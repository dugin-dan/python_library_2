Библиотеки Python для Data Science: продолжение

Задача

Требуется, на основании имеющихся данных о клиентах банка, построить модель, используя обучающий датасет, для прогнозирования невыполнения долговых обязательств по текущему кредиту. Выполнить прогноз для примеров из тестового датасета.

Целевая переменная

Credit Default - факт невыполнения кредитных обязательств

Метрика качества

F1-score (sklearn.metrics.f1_score)

Требования к решению

Целевая метрика

    F1 > 0.5
    Метрика оценивается по качеству прогноза для главного класса (1 - просрочка по кредиту)

Рекомендации для файла с кодом (ipynb)

    Файл должен содержать заголовки и комментарии (markdown)
    Повторяющиеся операции лучше оформлять в виде функций
    Не делать вывод большого количества строк таблиц (5-10 достаточно)
    По возможности добавлять графики, описывающие данные (около 3-5)
    Добавлять только лучшую модель, то есть не включать в код все варианты решения проекта
    Скрипт проекта должен отрабатывать от начала и до конца (от загрузки данных до выгрузки предсказаний)
    Весь проект должен быть в одном скрипте (файл ipynb).
    Допускается применение библиотек Python и моделей машинного обучения, которые были в данном курсе.
