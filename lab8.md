# Лабораторная работа №7 "Python"

[Обратно к выбору лабораторной :back:](https://github.com/sadokhin/A1_Data_Visualization/blob/962705b6445b2bc117fa2d7bd38c10e4f1718aba/README.md)

> Датасет: [sales_data](https://drive.google.com/drive/folders/1AEiWXADWenoyEp-qngAA7Q27oULL6Xt1?usp=sharing)

__Записи уроков__

> [Лекция 1 "Анализ данных на Python ч.1"](https://youtu.be/vhrg_v69co4)
> 
> [Лекция 2 "Анализ данных на Python ч.2"]
> 
> [Лекция 3 "Анализ данных на Python ч.3"]


__Тетрадки Google Colab__

> [week8_lecture1.ipynb](https://colab.research.google.com/drive/1spXh8MkA9SSCpjtsdf03ZzE6GoDC-FpL?usp=sharing)
> 
> [week8_lecture2.ipynb]
> 
> [week8_lecture3.ipynb]

В данной лабораторной работе вам необходимо построить визуализации с помощью Python в Google Colab и ответить на вопросы в гугл-форме.

## Описание полей датасета

Данные о фильмах с сайта filmtv.it - самого популярного в Италии:

| Название столбца | Значение |
| -----------------|:--------:|
| filmtv_id | Идентификатор фильма |
| title |	Название |
| year |	Год премьеры |
| genre |	Жанр |
| duration | Продолжительность (мин) |
| country | Страна |
| directors |	Режиссеры |
| actors |	Актеры |
| avg_vote | Средний рейтинг |
| critics_vote | Рейтинг критиков |
| public_vote |	Рейтинг пользователей |
| total_votes |	Кол-во голосов |
| description |	Описание фильма |
| notes | Заметки к фильму |
| humor | Оценка юмора |
| rhythm |	Ритм, такт |
| efforts |	Старания |
| tension |	Напряжение |
| erotism | Эротизм |

## Задания

Вам необходимо открыть Google Colab, создать новый документ. Построить визуализации. Ответить на вопросы в гугл-форме, где нужно будет прикрепить ссылку на документ Google Colab. 

__1. Визуализации__

> Каждая визуализация в отдельной ячейке.
> Перед ячейкой с кодом диаграммы, должна быть ячейка с названием диаграммы жирным шрифтом.

- __Количество фильмов по жанрам__ : функция `barplot()` у библиотеки seaborn.
- __Распределение среднего рейтинга по жанрам__ : функция `boxplot()` у библиотеки seaborn.
- __Распределение фильмов по продолжительности в разрезе жанра__ : функция `histplot()` у библиотеки seaborn.
- __Средний ретинг и количество голосов у ТОП-20 фильмов__ : `Scatter()` у библиотеки plotly.

__2. Ответы на вопросы__
> [Ссылка на гугл форму](https://forms.gle/wK5fVu4AKCYmyWpR6)

Заполните гугл форму. Тут уж думаю, у вас не будет выбора, кроме как находить ответы с помощью Python 😑. Последние два вопроса - для обратной связи. Буду рад, если заполните, но они не обязательны.

__Желаю удачи в решении задач!__