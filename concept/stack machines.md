## Стековые машины
стековые машины (eng: stack machines) 

## Определение
Стековая виртуальная машина реализует основные, описанные свойства [виртуальной машины](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md) но в качестве структуры данных, куда помещаются операнды, используется [стек](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack.md).
## Пример
 Блок-схема «Классической Стековой Машины»:
 
 
![stack_machine](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/stack_machine.png "Блок-схема «Классической Стековой Машины»")

Каждый блок на схеме представляет часть машинной логики, соответствующей минимально необходимому компоненту конструкции. 

В число таких компонентов входят: 
 - [«шина данных»](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/data%20bus.md) ( data bus ), 
 - [«стек данных»](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/data%20stack.md) ( DS ),
 - [«стек адресов возврата» или просто «стек возврата»](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/stack%20of%20returns.md) ( RS ),
 - [«арифметическо-логическое устройство»](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/arithmetic%20logic%20unit.md) ( ALU ) с регистром «вершина стека» ( TOS ), 
 - «счетчик программы» ( PC ), 
 - «программная память» с «регистром адреса памяти» ( MAR ),
 - управляющая логика с «регистром инструкций» ( IR ) и секция «ввода-вывода» ( I/O ).



## Связь с другими понятиями

## Cсылка на библиографию
[tuesdays-stack-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/tuesdays-stack-book%7B1%7D.md)

