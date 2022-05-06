## Компилятор
компилятор(eng: compiler) 

## Определение
Компилятор —  программа, переводящая написанный на языке программирования текст в набор машинных кодов. 

## Примечание

Процесс компиляции состоит из следующих этапов:

 - [Лексический анализ](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/lexical%20analyzer.md). На этом этапе последовательность символов исходного файла преобразуется в последовательность лексем.

 - [Синтаксический (грамматический) анализ](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/parser.md). Последовательность лексем преобразуется в дерево разбора.

 - [Семантический анализ](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/semantic%20analyzer.md). Дерево разбора обрабатывается с целью установления его семантики (смысла) — например, привязка идентификаторов к их декларациям, типам, проверка совместимости, определение типов выражений и т. д. Результат обычно называется «промежуточным представлением/кодом», и может быть дополненным деревом разбора, новым деревом, абстрактным набором команд или чем-то ещё, удобным для дальнейшей обработки.

 - [Оптимизация](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/code%20optimization.md). Выполняется удаление излишних конструкций и упрощение кода с сохранением его смысла. Оптимизация может быть на разных уровнях и этапах — например, над промежуточным кодом или над конечным машинным кодом.

 - [Генерация кода](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/code%20generation.md). Из промежуточного представления порождается код на целевом языке.

В конкретных реализациях компиляторов эти этапы могут быть разделены или, наоборот, совмещены в том или ином виде.

Общая схема работы компилятора:

![compiler](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/compiler.png "Общая схема работы компилятора")

## Связь с другими понятиями

[виртуальная машина](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md)

[информационные таблицы](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/information%20tables.md)

[оптимизация кода](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/code%20optimization.md)

[код операции](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/operation%20code.md)

[интерпретатор](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/interpreter.md)

[компиляция](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/compiler.md)

[лексический анализатор](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/lexical%20analyzer.md)

[синтаксический анализатор](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/parser.md)

[семантический анализатор](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/semantic%20analyzer.md)
             
[генерация промежуточного кода](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/code%20generation.md)
         
[байт-код](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/byte-code.md)
         
[машинный код](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/machine%20code.md)
         

## Cсылка на библиографию
[aho-compilers-book{5}](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/aho-compilers-book%7B5%7D.md)

