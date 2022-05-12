## Обратная польская запись 
oбратная польская запись(eng: reverse polish notation) 

## Определение
Обратная польская запись — форма записи математических и логических выражений, в которой операнды расположены перед знаками операций. 
## Примечание
Отличительной особенностью обратной польской нотации является то, что все аргументы (или [операнды](operand.md)) расположены перед знаком операции. В общем виде запись выглядит следующим образом:

Запись набора операций состоит из последовательности [операндов](operand.md) и знаков операций. [Операнды](operand.md) в выражении при письменной записи разделяются пробелами.
Выражение читается слева направо. Когда в выражении встречается знак операции, выполняется соответствующая операция над двумя последними встретившимися перед ним операндами в порядке их записи. Результат операции заменяет в выражении последовательность её операндов и её знак, после чего выражение вычисляется дальше по тому же правилу.

Результатом вычисления выражения становится результат последней вычисленной операции.

[Стековой машиной](stack%20machines.md) называется алгоритм, проводящий вычисления по обратной польской записи.

[Стековые машины](stack%20machines.md) проводят действия с данными, используя постфиксные операции. Такие операции обычно называются «обратные польские» по аналогии с «обратной польской записью» ( RPN ), часто используемой для описания постфиксных операций. Их особенностью является то, что операнды идут впереди символа операции.


## Связь с другими понятиями
[стек](stack.md)
## Cсылка на библиографию
[tuesdays-stack-book{3}](../bibliography/tuesdays-stack-book%7B3%7D.md)
