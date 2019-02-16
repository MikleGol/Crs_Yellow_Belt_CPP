# Программа курса "Желтый пояс С++"
Во всех программах используется директива using namespace std.
Код не менял, хочу посмотреть на него через пару-тройку лет.

## Week 1
Материалы этой недели знакомят вас с возможностями языка C++,
не рассмотренными в курсе «Белый пояс по C++». Сначала рассмотрены
различные целочисленные типы языка C++, рассказано, чем они отличаются,
а также даны практические рекомендации по их применению. Затем
рассматриваются пары и кортежи как способ упростить возврат нескольких
значений из функций и создание операторов сравнения для своих классов.
Наконец, мы расскажем о шаблонах функций. «Когда будут шаблоны?» был
одним из самых частых вопросов, которые нам задавали слушатели
«Белого пояса». Тема эта обширная и сложная, поэтому мы начинаем
с малого — рассказываем о шаблонах функций: что это такое, для чего
они нужны и как их создавать.

* Целочисленные типы
* Кортежи и пары
* Шаблоны функций

## Week 2
Эта неделя посвящена использованию юнит-тестов для тестирования
и отладки программ. На примере мы продемонстрируем, как юнит-тесты
помогают в поиске и устранении ошибок, а также что нужно делать, чтобы
покрыть свой код юнит-тестами. Затем с помощью накопленных на данный
момент знаний мы разработаем свой собственный фреймворк для создания
юнит-тестов, которым вы сможете пользоваться в своих программах.

* Использование юнит-тестов для отладки программ
* Разработка фреймворка юнит-тестов. Начало
* Разработка фреймворка юнит-тестов. Окончание. Итоги

## Week 3
Весь код, который мы прежде писали в нашем курсе, всегда находился
в одном файле. Естественно, реальные большие проекты не пишутся
в одном файле. В материалах этой недели мы рассмотрим, как распределять
код программ на C++ на несколько файлов. Мы расскажем, что такое
заголовочные файлы и файлы с реализациями, как работает директива #include
и как выполняется сборка многофайлового проекта. Кроме того,
мы поговорим о проблемах, которые возникают в больших проектах
и расскажем, как их решать.

* Заголовочные файлы
* Многофайловые проекты

## Week 4
В курсе "Белый пояс по C++" мы познакомились с некоторыми стандартными
алгоритмами: count, count_if и sort. Конечно же, библиотека C++
гораздо богаче и содержит значительно больше стандартных алгоритмов,
которые позволяют сделать ваш код короче, понятнее и надёжнее.
Чтобы их освоить, сначала нужно узнать, что такое итераторы. С этого
мы и начнём четвёртую неделю. Затем рассмотрим стандартные алгоритмы,
в которых используются итераторы. Наконец, мы познакомим вас с новыми
стандартными контейнерами: деком и очередью.

* Введение в итераторы
* Использование итераторов в алгоритмах и контейнерах
* Очередь, дек и алгоритмы поиска

## Week 5
Объектно-ориентированное программирование стоит на трёх китах:
инкапсуляция, наследование и полиморфизм. О том, какими средствами
достигается инкапсуляция в C++, мы узнали в "Белом поясе по C++".
Эта неделя расскажет вам о двух оставшихся "китах": наследовании
и полиморфизме. Мы не только покажем, как именно в C++ унаследовать
один класс от другого и создать набор полиморфных объектов,
но и применим полученные знания на практике - создадим
программу-калькулятор, которая поддерживает работу с переменными.

* Наследование
* Полиморфизм

## Week 6
Настало время закрепить все полученные на курсе знания, применив их
в финальном проекте. Задача этой недели является развитием финального
проекта курса "Белый пояс по C++". Вам точно так же надо будет
разработать базу данных, которая хранит набор событий и поддерживает
различные операции с ним.

* Курсовой проект: База данных - продолжение.