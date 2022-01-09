# Домашнее задание к лекции «Select-запросы, выборки из одной таблицы»

### Задание 1

Заполните базу данных из предыдущего домашнего задания. В ней должно быть:

* не менее 8 исполнителей;
* не менее 5 жанров;
* не менее 8 альбомов;
* не менее 15 треков;
* не менее 8 сборников.
Внимание! Должны быть заполнены все поля каждой таблицы, в т.ч. таблицы связей (исполнителей с жанрами, исполнителей с альбомами, сборников с треками).

### Задание 2
Написать SELECT-запросы, которые выведут информацию согласно инструкциям ниже.
Внимание! Результаты запросов не должны быть пустыми (учтите при заполнении таблиц).

1. название и год выхода альбомов, вышедших в 2018 году;
2. название и продолжительность самого длительного трека;
3. название треков, продолжительность которых не менее 3,5 минуты;
4. названия сборников, вышедших в период с 2018 по 2020 год включительно;
5. исполнители, чье имя состоит из 1 слова;
6. название треков, которые содержат слово "мой"/"my".

Результатом работы будет 3 файла (с INSERT, SELECT запросами и CREATE запросами из предыдущего задания) в формате .sql (или .py/.ipynb, если вы будете писать запросы с использованием SQLAlchemy).