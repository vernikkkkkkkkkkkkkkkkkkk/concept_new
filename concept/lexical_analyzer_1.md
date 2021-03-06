## Лексический анализатор
лексический анализатор(eng: lexical analyzer) 

## Определение
Лексический анализатор — часть [компилятора](compiler_1.md), которая читает исходную программу и выделяет в ее тексте лексемы входного языка. На вход лексического анализатора поступает текст исходной программы.
## Примечание

Результатом работы лексического анализатора является перечень всех найденных в тексте исходной программы лексем. Этот перечень лексем можно представить в виде таблицы, называемой таблицей лексем . Каждой лексеме в таблице лексем соответствует некий уникальный условный код, зависящий от типа лексемы, и дополнительная служебная информация. Кроме того, информация о некоторых типах лексем, найденных в исходной программе, должна помещаться в таблицу идентификаторов (или в одну из таблиц идентификаторов, если компилятор предусматривает различные таблицы идентификаторов для различных типов лексем).

Известно два главных вида лексических анализаторов:

 - Прямые анализаторы.

 - Непрямые анализаторы.

Прямой лексический анализатор находит лексему, которая расположена правее текущего указателя, и выполняет сдвиг указателя вправо от текстового участка, определяющего лексему. 

Непрямой анализатор анализирует, формируют ли знаки, находящиеся правее указателя, лексему данного типа.

Общая схема работы лексического анализатора:

![lexical analyzer](images/lexical%20analyzer.png "Общая схема работы лексического анализатора")

## Генераторы лексических анализаторов

lex — стандартный генератор в Unix

Flex — альтернативный вариант классической утилиты lex

JLex — генератор на Java

ANTLR

lexertl

## Связь с другими понятиями
[компилятор](compiler_1.md)
## Cсылка на библиографию
[aho-compilers-book{8}](../bibliography/aho-compilers-book%7B8%7D.md)
