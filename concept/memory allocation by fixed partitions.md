## Распределение памяти фиксированными разделами
распределение памяти фиксированными разделами (eng: memory allocation by fixed partitions) 

## Определение
Распределение памяти фиксированными разделами — [память](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/memory.md) разбивается на несколько областей фиксированной величины, называемых разделами.
## Примечание

Такое разбиение (на несколько областей фиксированной величины) может быть выполнено вручную оператором во время старта системы или во время ее установки. После этого границы разделов не изменяются.

![memory allocation by fixed partitions](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/memory%20allocation%20by%20fixed%20partitions.png)

Подсистема управления памятью в этом случае выполняет следующие
задачи:

- сравнивая размер программы, поступившей на выполнение, и
свободных разделов, выбирает подходящий раздел,

- осуществляет загрузку программы и настройку адресов.
## Связь с другими понятиями

## Cсылка на библиографию
[karanchuk-fundamentals-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/karanchuk-fundamentals-book.md)
