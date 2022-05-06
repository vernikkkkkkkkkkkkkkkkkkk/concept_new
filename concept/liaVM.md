## Виртуальная машина Lia
виртуальная машина "lia"(eng: lia virtual machines)
## Определение 
Lua VM — [регистровая машина](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register%20machines.md). Интерпретатор Lua представляет собой [виртуальную машину](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md) с [байт-кодом](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/byte-code.md).
[Интерпретатор](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/interpreter.md) сначала просматривает текст программы, чтобы преобразовать его в последовательность инструкций [байт-кода](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/byte-code.md) для виртуального процессора, 
а затем используется простой while-switch цикл диспетчеризации для запуска программы, по одной инструкции за раз.
## Примечание
До версии 5.0 виртуальная машина Lua была [стековой машиной](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack%20machines.md). 
Раньше он работал с одним последовательным, расширяемым стеком значений, выталкивая и извлекая значения из вершины стека. 
Виртуальная машина 5.0 — это [регистровая машина](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register%20machines.md), которая работает с набором виртуальных [регистров](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register.md), которые могут хранить 
локальные переменные функции и воздействовать на них в дополнение к традиционному стеку времени выполнения.
