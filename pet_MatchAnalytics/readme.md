# Небольшой проект в области футбольной аналитики

### Цель: построение дашборда с результатами по любому* прошедшему матчу из основных топ-чемпионатов (в данном проекте приемущественно по ударам и xG**)

" * " данные о матче на сайте обычно появляются в течении часа после окончания матча 

" ** " xG - expected goals или показатель ожидаемых голов


Проект состоит из двух частей: парсинг даты с подготовкой исходного датасета и визуализация в Tableau

## Часть 1. Подготовка датасета 

Код извлечения данных с портала [understat.com](https://understat.com/) смотри файл "pet_MatchAnalytics_fooball_scraping_data_understat.ipynb" 

## Часть 2. Визуализация, построение дашборда со статистикой

Визуализация выполнялась в Tableau, для связи странички с парсингом в *Colab* и загрузки данных в *Tableau* использован *Google Drive* 

Дашборды автоматически перестраиваются после очередного подключения к файлам на облаке. 
Для удобства восприятия можно менять цвета команд домашней (h) и гостевой (a), зайдя в настройки "Colors" переменной "h_a". В примерах ниже цвета изменены согласно цветовой палитре комплектов форме команд.
Готовый результат: 2 дашборда с информацией о xG команд и статистикой матча.

#Пример 1. Один из первых матчей 2022 года. Матч лидеров АПЛ Челси - Ливерпуль. 
* [Дашборд Челси - Ливерпуль №1](https://public.tableau.com/app/profile/vlad.ivanov/viz/MatchResult_ex1_xG/MatchResults2)
* [Дашборд Челси - Ливерпуль №2](https://public.tableau.com/app/profile/vlad.ivanov/viz/MatchResult_ex1_shots/MatchResults)

#Пример 2. Декабрьский матч московского Спартака в РПЛ.
* [Дашборд Cпартак - ФК Ахмад №1](https://public.tableau.com/app/profile/vlad.ivanov/viz/MatchResult_ex2_xG/MatchResults2)
* [Дашборд Cпартак - ФК Ахмад №2](https://public.tableau.com/app/profile/vlad.ivanov/viz/MatchResult_ex2_shots/MatchResults)

#Пример 3. Матч Серии-А Рома-Милан. Forza Milan! 
* [Дашборд Рома - Милан №1](https://public.tableau.com/app/profile/vlad.ivanov/viz/MatchResult_ex3_xG/MatchResults2)
* [Дашборд Рома - Милан №2](https://public.tableau.com/app/profile/vlad.ivanov/viz/MatchResult_ex3_shots/MatchResults)


