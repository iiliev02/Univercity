Задача 1.

Напишете функция Allocate, която заделя в динамична памет, двумерен масив от цели числа с n реда (n > 1),
в нулевия ред на който има 1 елемент, в първия ред 2 елемента и т. н. в n - 1-ред има n елемента. 
Функцията също така и инициализира масива. В нулевия ред се записва числото 1; в първия ред числата 1 и 1;
във втория ред числата 1, 2, 1; в следващия ред числата 1, 3, 3, 1; и т. н. С други думи, в динамичния
масив се записва триъгълника на Паскал.
 - Напишете функция Print, която отпечатва съдържанието на масива по редове.
 - Напишете функция Deallocate, която освобождава паметта за динамичния масив от точка а).
 
 Задача 2.
 
 Като използвате класа Rational, пресметнете частичните суми (като несъкратими дроби) от първите n члена на двата числови реда, n = 1, 2, 3 ... и продължете докато превъртите типа long long int, в който се записват числителите и знаменателите на дробите. Като използвате метода toDouble() от класа Rational, изчислете и грешките на приближенията ln(2) и п/4 с частичните суми.
  - 1 - (1/2) + (1/3) - (1/4) +(1/5) - ..... = ln(2)
  - 1 - (1/3) + (1/5) - (1/7) +(1/9) - ..... = п/4
