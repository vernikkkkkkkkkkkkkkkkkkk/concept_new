## Веб-асемблер
веб-асемблер (eng: wasm) 

## Определение
WebAssembly ( Wasm ) определяет переносимый формат двоичного кода и соответствующий текстовый формат для исполняемых программ, 
а также программные интерфейсы для облегчения взаимодействия между такими программами и их хост-средой.
## Примечание
Код Wasm ([байт-код](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/byte-code.md)) предназначен для запуска на портативной машине виртуального стека ([ВМ](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md)).
[Виртуальная машина](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md) предназначена для более быстрого анализа и выполнения, чем JavaScript, и имеет компактное представление кода.
Внешняя функциональность (например , системные вызовы), которую можно ожидать от двоичного кода Wasm, 
не предусмотрена стандартом. 
Это скорее обеспечивает способ обеспечения взаимодействия через модули хост-средой, в которой работает реализация [виртуальной машины](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md). 
## Представление кода
В приведенной ниже таблице показан пример факториальной функции, написанной на C , и соответствующего ей кода WebAssembly после компиляции, 
представленного как в текстовом формате .wat (удобочитаемое текстовое представление WebAssembly), так и в двоичном формате .wasm 
(необработанный байт -код , выраженный ниже в шестнадцатеричном формате ), 
который выполняется веб-браузером или средой выполнения, поддерживающей WebAssembly.

Исходный код C и соответствующий WebAssembly:

![wasm](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/wasm.png)
## Cвязь с другими понятиями 
[набор команд веб-асемблера](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/command%20set%20wasm.md)
