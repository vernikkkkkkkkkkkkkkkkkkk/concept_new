## Промежуточная генерация кода
промежуточная генерация кода(eng: сode generation) 

## Определение
Промежуточная генерация кода — часть [процесса компиляции](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/compilation%20process.md), когда специальная часть [компилятора](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/compiler.md), кодогенератор, конвертирует синтаксически корректную программу в последовательность инструкций, которые могут выполняться на машине. При этом могут применяться различные, в первую очередь машинно-зависимые оптимизации. Часто кодогенератор является общей частью для множества [компиляторов](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/compiler.md). Каждый из них генерирует промежуточный код, который подаётся на вход кодогенератору.
## Способы представления
Промежуточные коды могут быть представлены различными способами:

High Level IR – высокоуровневое представление промежуточного кода очень близко к самому исходному языку. Они могут быть легко сгенерированы из исходного кода, и мы можем легко применить модификации кода для повышения производительности. Но для оптимизации целевой машины это менее предпочтительно.

Низкоуровневое ИК – Это устройство близко к целевой машине, что делает его пригодным для распределения регистров и памяти, выбора набора команд и т. д. Это хорошо для машинно-зависимых оптимизаций.

[Промежуточный код](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/byte-code.md) может быть либо специфичным для языка (например, Байт-код для Java), либо независимым от языка (трехадресный код).
## Пример
Промежуточная генерация кода:

![сode generation](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/intermediate_code.png)

## Связь с другими понятиями
[компилятор](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/compiler.md)
## Cсылка на библиографию
[harris-architecture-book{3}](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/bibliography/harris-architecture-book%7B3%7D.md)


