## Курсовая работа
### Моделирование работы инженерного арифметического калькулятора
В данной курсовой работе необходимо смоделировать работу калькулятора следующей конструкции:
- в вычислении участвуют целые числа объемом памяти 2 байта;
- допустимые операции: +, -, *, / (целочисленное деление), % (деление с остатком), << (побитовый сдвиг влево), >> (побитовый сдвиг в право);
- операции выполняются последовательно, для выполнения операции необходимы два аргумента и знак операции;
- после выполнения каждой операции фиксируется и выводится результат; 
- последовательность операций и аргументов образует выражение;
- результат отображается в 16, 10 и 2-ой системе счисления;
- при возникновении переполнения выдается Overflow;
- при попытке деления на 0 выдается Division by zero;
- при вводе знака “C” калькулятор приводиться в исходное состояние, первый аргумент выражения принимает значение 0 и готов для ввода очередного выражения;
- при вводе знака “Off” калькулятор завершает работу.

Нажатие на клавиши калькулятора моделируется посредством клавиатурного ввода. Ввод делится на команды:
1. «целое число» - первый аргумент выражения, целое не отрицательное число, можно последовательно вводить несколько раз, предыдущее значение меняется. При вводе не первым аргументом выражения - игнорируется;
2. «знак операции» «целое число» - второе и последующие операции выражения;
3. «C» - приведение калькулятора в исходное состояние;
4. «Off» - завершение работы калькулятора.
