16. Циклы
==============

### Контрольный список

#### Выбор и создание цикла 

+ Используется ли цикл while вместо цикла for, если он больше подходит? 
+ Создавался ли цикл изнутри наружу? 

#### Вход в цикл 

+ Выполняется ли вход в цикл сверху? 
+ Расположен ли код инициализации непосредственно перед циклом? 
+ Если необходим бесконечный или событийный цикл, конструируется ли он явно, или сделан такой ляп, как for i = 1 to 9999? 
+ В цикле for в C++, C или Java резервируется ли заголовок цикла только для управляющего кода? 

#### Тело цикла 

+ Использует ли цикл скобки { и } или их эквиваленты для обрамления тела цикла и предотвращения проблем, связанных с неправильной модификацией? 
+ Содержит ли тело цикла хоть что-то? Не пустое ли оно? 
+ Сгруппированы ли служебные операции в начале или конце цикла? 
+ Выполняет ли цикл одну и только одну функцию, как это делает хорошо спроектированный метод? 
+ Достаточно ли цикл короткий, чтобы его можно было сразу увидеть целиком? 
+ Не превышает ли вложенность цикла трех уровней? 
+ Вынесено ли содержимое длинного цикла в отдельный метод? 
+ Если цикл достаточно длинный, написан ли он особенно ясно? 

#### Индексы цикла 

+ Если это цикл for, не выполняются ли манипуляции с индексом цикла внутри самого цикла? 
+ Используется ли для сохранения важных значений индекса цикла вне этого цикла специальная переменная, а не сам индекс цикла? 
+ Является ли индекс цикла порядковым или перечислимым типом, но не типом с плавающей запятой? 
+ Имеет ли индекс цикла смысловое имя? 
+ Не содержит ли цикл пересечения индексов? 

#### Завершение цикла 

+ Завершается ли цикл при всех возможных условиях? 
+ Использует ли цикл счетчики безопасности, если они приняты на уровне стандарта? 
+ Очевидно ли условие завершения цикла? 
+ Если используются операторы break или continue, корректны ли они? 

### Ключевые моменты 

+ Циклы сложны для понимания. Сохраняя их простыми, вы помогаете читателям вашего кода. 
+ К способам упрощения циклов относятся: избегание экзотических видов циклов, минимизация вложенности, создание очевидных входов и выходов цикла и хранение служебного кода в одном месте. 
+ Индексы цикла часто употребляются неправильно. Называйте их понятно и используйте только с одной целью. 
+ Аккуратно продумайте весь цикл, чтобы убедиться, что он работает правильно во всех случаях и завершается при любых возможных обстоятельствах.