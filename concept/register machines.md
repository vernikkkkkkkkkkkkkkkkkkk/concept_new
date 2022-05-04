## Регистровые машины
регистровые машины (eng: register machines) 

## Определение
Регистровая машина состоит из конечного числа регистров, хранящих неотрицательные целые числа и управляющий программный блок, который выполняет операции над содержимым регистров согласно программе (упорядоченной последовательности команд).

В качестве регистровой виртуальной машины можно назвать Lua VM и Dalvik VM.

В регистровой реализации виртуальной машины структура данных, в которую помещаются операнды, основана на регистрах процессора. При этом не требуются операции PUSH или POP, но инструкции должны явно содержать адреса (регистры) в которых содержатся операнды. То есть, операнды для инструкций, в отличии от стековой модели, указываются явно. 

Пример работы регистровой машины на основе операции сложения:

![register_add](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/registeradd.png)

За счет отсутствия операций POP и PUSH команды в регистровой виртуальной машине выполняются достаточно быстро.

Регистровые машины позволяют провести оптимизацию, например несколько раз встречающееся выражение при регистровом подходе может быть вычислено лиш однажды и сохранено в регистре для последующего использования, что экономит время необходимое для пересчета выражения.

Схема регистровой машины:

![register machine](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/register_machine.svg)

На иллюстрации приведена условная схема “регистровой машины”, которая состоит из трёх частей: процессора, выполняющего операции над натуральными числами, программы (ПЗУ), которая представляет собой последовательность пронумерованных инструкций и памяти (ОЗУ), состоящей из пронумерованных регистров.

## Cвязь с другими понятиями 
[virtual machines](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/virtual%20machines.md)

[stack machines](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/stack%20machines/stack%20machines.md)

[register machines](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/register%20machines.md)

[memory management](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/memory%20management/memory%20management.md)

[instruction set](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/instruction%20set/instruction%20set.md)

[examples](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/tree/main/virtual%20machines/examples%20of%20virtual%20machines%20used%20with%20programming%20languages)

[abstract automaton](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/abstract%20automaton.md)

[algorithm](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/algorithm.md)

[expression trees](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/expression%20trees.md)

[external alphabet](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/external%20alphabet.md)

[finite state machine](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/finite%20state%20machine.md)

[internal alphabet](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/internal%20alphabet.md)

[nondeterministic turing machine](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/nondeterministic%20turing%20machine.md)

[process control block](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/process%20control%20block.md)

[program](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/program.md)

[register](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/register.md)

[transition table](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/transition%20table.md)

[turing machine](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/register%20machines/turing%20machine.md)
## Cсылка на библиографию
[savitsky-calculations-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/bibliography/register%20machines/savitsky-calculations-book.md)

