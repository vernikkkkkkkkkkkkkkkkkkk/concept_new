## Регистровые машины
регистровые машины (eng: register machines) 

## Определение
Регистровая машина состоит из конечного числа [регистров](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register.md), хранящих неотрицательные целые числа и управляющий программный блок, который выполняет операции над содержимым регистров согласно программе (упорядоченной последовательности команд).
## Примечание
В качестве регистровой виртуальной машины можно назвать [Lua VM](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/liaVM.md) 
и [Dalvik VM](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/dalvik.md).

В регистровой реализации [виртуальной машины](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md) структура данных, в которую помещаются [операнды](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/operand.md), основана на [регистрах](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register.md) [процессора](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/processor.md). При этом не требуются операции PUSH или POP, но инструкции должны явно содержать адреса ([регистры](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register.md)) в которых содержатся [операнды](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/operand.md). То есть, [операнды](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/operand.md) для инструкций, в отличии от стековой модели, указываются явно. 

## Пример
Пример работы регистровой машины на основе операции сложения:

![register_add](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/registeradd.png)

За счет отсутствия операций POP и PUSH команды в регистровой виртуальной машине выполняются достаточно быстро.

Регистровые машины позволяют провести [оптимизацию](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/code%20optimization.md), например несколько раз встречающееся выражение при регистровом подходе может быть вычислено лиш однажды и сохранено в [регистре](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register.md) для последующего использования, что экономит время необходимое для пересчета выражения.

Схема регистровой машины:

![register machine](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/register_machine.svg)

На иллюстрации приведена условная схема “регистровой машины”, которая состоит из трёх частей: [процессора](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/processor.md), выполняющего операции над натуральными числами, программы (ПЗУ), которая представляет собой последовательность пронумерованных инструкций и памяти (ОЗУ), состоящей из пронумерованных регистров.

## Cвязь с другими понятиями 

## Cсылка на библиографию
[savitsky-calculations-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/savitsky-calculations-book.md)
