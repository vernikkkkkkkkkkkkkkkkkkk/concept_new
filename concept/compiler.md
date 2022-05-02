## Компилятор
компилятор(eng: compiler) 

## Определение
Компилятор —  программа, переводящая написанный на языке программирования текст в набор машинных кодов. 

Процесс компиляции состоит из следующих этапов:

Лексический анализ. На этом этапе последовательность символов исходного файла преобразуется в последовательность лексем.

Синтаксический (грамматический) анализ. Последовательность лексем преобразуется в дерево разбора.

Семантический анализ. Дерево разбора обрабатывается с целью установления его семантики (смысла) — например, привязка идентификаторов к их декларациям, типам, проверка совместимости, определение типов выражений и т. д. Результат обычно называется «промежуточным представлением/кодом», и может быть дополненным деревом разбора, новым деревом, абстрактным набором команд или чем-то ещё, удобным для дальнейшей обработки.

Оптимизация. Выполняется удаление излишних конструкций и упрощение кода с сохранением его смысла. Оптимизация может быть на разных уровнях и этапах — например, над промежуточным кодом или над конечным машинным кодом.

Генерация кода. Из промежуточного представления порождается код на целевом языке.

В конкретных реализациях компиляторов эти этапы могут быть разделены или, наоборот, совмещены в том или ином виде.

Общая схема работы компилятора:

![compiler](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/compiler.png "Общая схема работы компилятора")

## Связь с другими понятиями

[virtual machines](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/virtual%20machines.md)

[address space](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/address%20space.md)

[cooperative multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/cooperative%20multitasking.md)

[emulation](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/emulation.md)

[file descriptor](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/file%20descriptor.md)

[hardware](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/hardware.md)

[host-platform](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/host-platform.md)

[multiprocessing](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multiprocessing.md)

[multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multitasking.md)

[multithreading](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multithreading.md)

[multiuser system](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multiuser%20system.md)

[nonpreepmtive multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/nonpreepmtive%20multitasking.md)

[operating systems](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/operating%20systems.md)

[preemptive multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/preemptive%20multitasking.md)
 
[software system](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/software%20system.md)

[symmetric multiprocessing](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/symmetric%20multiprocessing.md)

[target platform](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/target%20platform.md)

[tightly-coupled multiprocessor systems](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/tightly-coupled%20multiprocessor%20systems.md)

[virtualization](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/virtualization.md)

[cluster](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/%D1%81luster.md)
## Cсылка на библиографию
[denisov-procuring-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/bibliography/virtual%20machines/denisov-procuring-book.md)


