## Интерпретатор
интерпретатор(eng: interpreter) 

## Определение
Интерпретатор — переводит и выполняет программу строка за строкой, производит пооператорный (покомандный, построчный) анализ, обрабатывает и тут же выполняет исходную программу или запроса (в отличие от компиляции, при которой программа транслируется без её выполнения.

Типы интерпретаторов:

Простой интерпретатор анализирует и тут же выполняет (собственно интерпретация) программу покомандно (или построчно), по мере поступления её исходного кода на вход интерпретатора. Достоинством такого подхода является мгновенная реакция. Недостаток — такой интерпретатор обнаруживает ошибки в тексте программы только при попытке выполнения команды (или строки) с ошибкой.

Интерпретатор компилирующего типа — это система из компилятора, переводящего исходный код программы в промежуточное представление, например, в байт-код или p-код, и собственно интерпретатора, который выполняет полученный промежуточный код (так называемая виртуальная машина). Достоинством таких систем является большее быстродействие выполнения программ (за счёт выноса анализа исходного кода в отдельный, разовый проход, и минимизации этого анализа в интерпретаторе). Недостатки — большее требование к ресурсам и требование на корректность исходного кода. Применяется в таких языках, какJava,Tcl,Perl(используется байт-код), а также в различных СУБД.

Общая схема работы интерпретатора:

![interpreter](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/intepretator.png "Общая схема работы интепретатора")

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


