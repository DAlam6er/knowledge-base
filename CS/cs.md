## В состав Computer Science любого языка программирования входят:
![Содержание CS](resources/05.png)

## Языки программирования и области их применения

Языков программирования существует большое количество, 
потому что каждый из них занимает определенную нишу.

Не существует универсального ЯП, который можно было бы использовать для всего.

Области применения языков программирования

![Области применения языков программирования](resources/01.png)

## Компиляторы

Файлы с исходным кодом читаются людьми, но их содержание непонятно 
компьютеру. 
Поэтому существуют __компиляторы__.

__Компиляторы__ — это программы, которые тоже написаны на одном из языков 
программирования, чтобы преобразовать один тип кода в другой.

![Компилятор](resources/02.png)

Скомпилированный код отличается в зависимости от операционной системы:

![Зависимость кода от платформы](resources/03.png)

Таким образом, под каждую ОС или новую версию процессора придется 
перекомпилировать исходный код, что очень неудобно.

В случае Java решением этой проблемы стало создание JVM (Java Virtual 
Machine) - программа, которая интерпретирует __байт-код__ (*class) в 
машинный код.

![Работа JVM](resources/04.png)

Каждая из JVM, установленная на соответствующей платформе, знает как 
преобразовывать байт-код в работоспособный машинный код, характерный 
для данной конкретной платформы. Именно это позволило не 
перекомпилировать код множество раз.
