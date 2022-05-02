## Стековый кадр
cтековый кадр (eng: stack frame) 

## Определение
Стековый кадр - механизм передачи аргументов и выделения временной памяти (в процедурах языков программирования высокого уровня) с использованием системного стека.

Передача аргументов

При вызове процедуры аргументы отправляются в стек, и только потом производится вызов подпрограммы. Таким образом, процедура получает стек, на вершине которого лежит адрес возврата, а под ним — аргументы, с которыми она была вызвана.

При возвращении из процедуры аргументы должны быть сняты со стека.

Выделение временной памяти:

Если указатель стека сместить «выше» (в сторону увеличения стека), то часть памяти в стеке окажется незадействованной (в том числе и при вызове третьей процедуры) и может использоваться процедурой по своему усмотрению, вплоть до момента возврата в вызвавшую её процедуру. Таким образом, языки высокого уровня организуют переменные, существующие только внутри процедуры.

Перед возвратом процедура должна вернуть указатель стека в оригинальное положение (то есть на адрес возврата).

## Связь с другими понятиями

[stack machines](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/stack%20machines.md)

[arithmetic logic unit](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/arithmetic%20logic%20unit.md)

[bus](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/bus.md)

[data buffer](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/data%20buffer.md)

[data bus](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/data%20bus.md)

[data stack](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/data%20stack.md)

[data structure](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/data%20structure.md)

[instruction counter](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/instruction%20counter.md)

[interrupt handler](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/interrupt%20handler.md)

[operand](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/operand.md)

[pushdown automaton](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/pushdown%20automaton.md)

[stack of returns](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/stack%20of%20returns.md)

[stack](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/stack.md)
## Cсылка на библиографию
[babenko-introduction-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/bibliography/stack%20machines/babenko-introduction-book.md)

