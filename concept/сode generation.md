## Промежуточная генерация кода
промежуточная генерация кода(eng: сode generation) 

## Определение
Промежуточная генерация кода — часть процесса компиляции, когда специальная часть компилятора, кодогенератор, конвертирует синтаксически корректную программу в последовательность инструкций, которые могут выполняться на машине. При этом могут применяться различные, в первую очередь машинно-зависимые оптимизации. Часто кодогенератор является общей частью для множества компиляторов. Каждый из них генерирует промежуточный код, который подаётся на вход кодогенератору.

Промежуточные коды могут быть представлены различными способами:

High Level IR – высокоуровневое представление промежуточного кода очень близко к самому исходному языку. Они могут быть легко сгенерированы из исходного кода, и мы можем легко применить модификации кода для повышения производительности. Но для оптимизации целевой машины это менее предпочтительно.

Низкоуровневое ИК – Это устройство близко к целевой машине, что делает его пригодным для распределения регистров и памяти, выбора набора команд и т. д. Это хорошо для машинно-зависимых оптимизаций.

Промежуточный код может быть либо специфичным для языка (например, Байт-код для Java), либо независимым от языка (трехадресный код).

Промежуточная генерация кода:

![сode generation](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/intermediate_code.png)

## Связь с другими понятиями

[virtual machines](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/virtual%20machines.md)

[address space](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/address%20space.md)

[cooperative multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/cooperative%20multitasking.md)

[emulation](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/emulation.md)

[file descriptor](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/file%20descriptor.md)

[hardware](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/hardware.md)

[host-platform](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/host-platform.md)

[multiprocessing](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multiprocessing.md)

[multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multitasking.md)

[multithreading](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multithreading.md)

[multiuser system](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/multiuser%20system.md)

[nonpreepmtive multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/nonpreepmtive%20multitasking.md)

[operating systems](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/operating%20systems.md)

[preemptive multitasking](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/preemptive%20multitasking.md)
 
[software system](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/software%20system.md)

[symmetric multiprocessing](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/symmetric%20multiprocessing.md)

[target platform](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/target%20platform.md)

[tightly-coupled multiprocessor systems](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/tightly-coupled%20multiprocessor%20systems.md)

[virtualization](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/virtualization.md)

[cluster](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/virtual%20machines/virtual%20machines/%D1%81luster.md)
## Cсылка на библиографию
[denisov-procuring-book](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept/blob/main/bibliography/virtual%20machines/denisov-procuring-book.md)


