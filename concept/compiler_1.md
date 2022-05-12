## Компилятор
компилятор(eng: compiler) 

## Определение
Компилятор —  программа, переводящая написанный на языке программирования текст в набор машинных кодов. 

## Примечание

Процесс компиляции состоит из следующих этапов:

 - [Лексический анализ](lexical%20analyzer.md). На этом этапе последовательность символов исходного файла преобразуется в последовательность лексем.

 - [Синтаксический (грамматический) анализ](parser.md). Последовательность лексем преобразуется в дерево разбора.

 - [Семантический анализ](semantic%20analyzer.md). Дерево разбора обрабатывается с целью установления его семантики (смысла) — например, привязка идентификаторов к их декларациям, типам, проверка совместимости, определение типов выражений и т. д. Результат обычно называется «промежуточным представлением/кодом», и может быть дополненным деревом разбора, новым деревом, абстрактным набором команд или чем-то ещё, удобным для дальнейшей обработки.

 - [Оптимизация](code%20optimization.md). Выполняется удаление излишних конструкций и упрощение кода с сохранением его смысла. Оптимизация может быть на разных уровнях и этапах — например, над промежуточным кодом или над конечным машинным кодом.

 - [Генерация кода](code%20generation.md). Из промежуточного представления порождается код на целевом языке.

В конкретных реализациях компиляторов эти этапы могут быть разделены или, наоборот, совмещены в том или ином виде.

Общая схема работы компилятора:

![compiler](../images/compiler.png)

## Примеры компилируемых языков
- C
- C++
- C#
- Go
- Swift
- Delphi
## Связь с другими понятиями

[виртуальная машина](virtual%20machines.md)

[информационные таблицы](information%20tables.md)

[оптимизация кода](code%20optimization.md)

[код операции](operation%20code.md)

[интерпретатор](interpreter.md)

[компиляция](compiler.md)

[лексический анализатор](lexical%20analyzer.md)

[синтаксический анализатор](parser.md)

[семантический анализатор](semantic%20analyzer.md)
             
[генерация промежуточного кода](code%20generation.md)
         
[байт-код](byte-code.md)
         
[машинный код](machine%20code.md)
         

## Cсылка на библиографию
[aho-compilers-book{5}](../bibliography/aho-compilers-book%7B5%7D.md)
