# Проект: Анализ пользовательского поведения в мобильном приложении


## Описание проекта
Стартап, который продаёт продукты питания. В процессе проведения анализа перед нами стоит две задачи:

Первая задача:
Изучить воронку продаж. Нам требуется узнать какой путь проходят пользователи до покупки и сколько из них "застревает" на каждом из этапов этого пути.

Вторая задача: Дизайнеры решили изменить шрифты в приложении, но учитывая радекальность этого решения, перед его воплощением провели A/A/B-эксперимент. Нам надо изучить его результаты, обратив внимание на идентичность групп A.
Нужно разобраться, как ведут себя пользователи мобильного приложения.

## Инструменты и навыки
- Библиотеки: pandas, numpy, scipy, plotly, matplotlib, seaborn
- A/B-тестирование
- поправка Бомферрони
- событийная аналитика
- продуктовые метрики
- проверка статистических гипотез
- визуализация данных

## Вывод
Мы убедились, что A/A-тест прошел успешно. Статистически значимых различий между двумя контрольными группами не обнаружено, это значит, что пользователи относятся к той или иной группе корректно. Если смотреть на результаты A/B-теста, то и там статистически значимых различий не было обнаружено, это говорит о том, что теория о том, что изменение шрифта в приложении может повлиять на метрики оказалась отвергнута. 
