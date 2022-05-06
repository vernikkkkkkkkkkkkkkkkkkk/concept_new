##  Распределение памяти перемещающимися разделами
распределение памяти перемещающимися разделами (eng: memory allocation by moving partitions) 

## Определение
Распределение памяти перемещающимися разделами — один из методов борьбы с фрагментацией - перемещение всех занятых участков в сторону старших либо в сторону младших адресов, так, чтобы вся свободная [память](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/memory.md) образовывала единую свободную область.

## Пример
![memory allocation by moving partitions](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/memory%20allocation%20by%20moving%20partitions.png)

Эта
процедура называется "сжатием". Сжатие может выполняться либо
при каждом завершении задачи, либо только тогда, когда для вновь
поступившей задачи нет свободного раздела достаточного размера.
В первом случае требуется меньше вычислительной работы при
корректировке таблиц, а во втором - реже выполняется процедура
сжатия. Так как программы перемещаются по оперативной памяти
в ходе своего выполнения, то преобразование адресов из
виртуальной формы в физическую должно выполняться
динамическим способом.
## Связь с другими понятиями
[управление памятью](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/memory%20management.md)
## Cсылка на библиографию
[tanenbaum-architecture-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/tanenbaum-architecture-book.md)
