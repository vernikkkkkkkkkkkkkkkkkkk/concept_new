## Далвик
далвик (eng: dalvik) 

## Определение
DALVIK – реализованная google виртуальная машина для Android и выполняющая функцию интерпретатора java кода на устройствах под управлением этой ОС. Для выполнения процесса Android создает отдельный экземпляр [виртуальной машины](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md). Это снижает вероятность краха системы при падении одного из приложений. Dalvik реализует регистровую модель и в отличаи от стандартного java [байткода](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/byte-code.md), который выполняет 8 битные инструкции на стековой [JVM](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/java%20virtual%20machine.md), использует 16 битные инструкции. [Регистры](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/register.md) реализованы в Dalvik в виде 4 битных полей.

## Примечание

Если мы хотим получить более детальную информацию о том как процесс получает экземпляр [виртуальной машины](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/virtual%20machines.md), мы должны начать рассмотрение с момента загрузки ядра Linux в Android:

![androidboot](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/androidboot.png)

Dalvik отличается от обычной [виртуальной машины Java](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/concept/java%20virtual%20machine.md) тем, что она выполняет байткод Dalvik, отличный от обычного java байткода. Промежуточный шаг между Java компилятором и Dalvik VM, на котором происходит преобразование Java байткода в байткод Dalvik берет на себя DEX компилятор. Раличие между JVM и Dalvik проилюстрировано на следующей диаграмме:

![dalvikoperation](https://github.com/vernikkkkkkkkkkkkkkkkkkk/concept_new/blob/main/images/dalvikoperation.png)

DEX компилятор преобразует .class файлы java в .dex файлы, которые имеют меньший размер и оптимизированы для Dalvik VM.

## Cвязь с другими понятиями 

