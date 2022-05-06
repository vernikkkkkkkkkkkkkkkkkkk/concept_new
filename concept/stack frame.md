## Стековый кадр
cтековый кадр (eng: stack frame) 

## Определение
Стековый кадр - механизм передачи аргументов и выделения временной памяти (в процедурах языков программирования высокого уровня) с использованием системного [стека](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md).
## Примечание
Передача аргументов:

При вызове процедуры аргументы отправляются в [стек](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md), и только потом производится вызов подпрограммы. Таким образом, процедура получает [стек](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md), на вершине которого лежит адрес возврата, а под ним — аргументы, с которыми она была вызвана.

При возвращении из процедуры аргументы должны быть сняты со [стека](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md).

Выделение временной памяти:

Если указатель [стека](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md) сместить «выше» (в сторону увеличения стека), то часть памяти в стеке окажется незадействованной (в том числе и при вызове третьей процедуры) и может использоваться процедурой по своему усмотрению, вплоть до момента возврата в вызвавшую её процедуру. Таким образом, языки высокого уровня организуют переменные, существующие только внутри процедуры.

Перед возвратом процедура должна вернуть указатель [стека](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md) в оригинальное положение (то есть на адрес возврата).

## Связь с другими понятиями
[стек](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md)
## Cсылка на библиографию
[babenko-introduction-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/babenko-introduction-book.md)
