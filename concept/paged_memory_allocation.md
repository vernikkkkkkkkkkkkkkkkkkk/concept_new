## Cтраничное распределение памяти
страничное распределение памяти (eng: paged memory allocation) 

## Определение
Страничное распределение памяти - это отображение виртуального адресного пространства, которое исключает внешнюю фрагментацию путем разбиения ОП на единицы одинаковой длины (в отличие от сегментации).


## Примечание
Блок-схема алгоритма обращения к страничной памяти (виртуальная память):

![ paged memory allocation](../images/paged%20memory%20allocation.png)

Блоки 1 - 7 -аппаратная реализация;
Блоки 8 - 17 -программная реализация.

Отличие от сегментации:

- разбиение программы на сегменты осуществляется пользователем;
- разбиение на страницы выполняется транслятором.

## Cвязь с другими понятиями 

[управление памятью](memory%20management.md)
## Список библиографии
[tanenbaum-systems-book](../bibliography/tanenbaum-systems-book.md)