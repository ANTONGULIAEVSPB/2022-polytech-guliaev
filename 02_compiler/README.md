g++ -O0 complex.cpp time: real 0m0,752s; user 0m0,749s; sys 0m0,001s

size: 25680; size of the text section: 00000234

g++ -O1 complex.cpp time: real 0m0,338s; user 0m0,337s; sys 0m0,000s

size: 25568; size of the text section: 000001e1

g++ -O2 complex.cpp time: real 0m0,187s; user 0m0,186s; sys 0m0,000s

size: 25776; size of the text section: 00000283

g++ -O3 complex.cpp time: real 0m0,155s; user 0m0,155s; sys 0m0,000s

size: 25752; size of the text section: 00000279

g++ -Os complex.cpp time: real 0m0,316s; user 0m0,313s; sys 0m0,002s

size: 25568; size of the text section: 000001a3

g++ -Ofast complex.cpp time: real 0m0,153s; user 0m0,152s; sys 0m0,001s

size: 25896 size of the text section: 000000d8

g++ -Og complex.cpp time: real 0m0,432s; user 0m0,418s; sys 0m0,000s

size: 25640; size of the text section: 000001d7

g++ -Oz complex.cpp time: real 0m0,501s; user 0m0,497s; sys 0m0,002s

size: 25568; size of the text section: 00000191

O0 — оптимизация кода не производится

O1 — применяются самые простые и очевидные способы оптимизации

O2 — применяются практически все доступные компилятору способы оптимизации, кроме тех, что ускоряют вычисления за счет увеличения размера кода, или тех, которые иногда могут,
наоборот, замедлить выполнение программы

O3 — применяются все доступные компилятору способы оптимизации

Os — применяются только те способы оптимизации, которые уменьшают не время выполнения программы, а размер машинного кода

Ofast — применяются все способы оптимизации уровня 03, а также добавляется ряд других

Og — применяются только те способы оптимизации, которые не сильно затрудняют отладку машинного кода

Oz — похож на 'Os' сильнее оптимизирует размер
