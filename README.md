# Python_course_GB_js
Решаем курс на js 
============dz_1=============
//------------------------------------------------------------------------------------------------------------
zadacha_2
Задача 2: Найдите сумму цифр трехзначного числа.
*Пример:*
123 -> 6 (1 + 2 + 3)
100 -> 1 (1 + 0 + 0)

Пользуемся делением и делением с остатком. Для округления используем метод Math.floor()

//------------------------------------------------------------------------------------------------------------
zadacha_4
Задача 4: Петя, Катя и Сережа делают из бумаги журавликов. Вместе они сделали S журавликов. Сколько журавликов сделал каждый ребенок, 
если известно, что Петя и Сережа сделали одинаковое количество журавликов, а Катя сделала в два раза больше журавликов, чем Петя и Сережа вместе?
*Пример:*
6 -> 1  4  1
24 -> 4  16  4
60 -> 10  40  10

x+x+(x+x)*2=s
6x=s
петя = s/6
серёжа = s/6
катя = (s/6)*4

//------------------------------------------------------------------------------------------------------------
zadacha_6
Задача 6: Вы пользуетесь общественным транспортом? Вероятно, вы расплачивались за проезд и получали билет с номером. Счастливым билетом называют такой билет с шестизначным номером,
где сумма первых трех цифр равна сумме последних трех. Т.е. билет с номером 385916 – счастливый, т.к. 3+8+5=9+1+6. 
Вам требуется написать программу, которая проверяет счастливость билета.
*Пример:*
385916 -> yes
123456 -> no  

Сделали цикл ввода диапозона 6ти значного числа, решаем через остаток и деление. Сравниваем полученные значения и выводим результат.

//------------------------------------------------------------------------------------------------------------
zadacha_8
Задача 8: Требуется определить, можно ли от шоколадки размером n × m долек отломить k долек, если разрешается 
сделать один разлом по прямой между дольками (то есть разломить шоколадку на два прямоугольника).
*Пример:*
3 2 4 -> yes
3 2 1 -> no

решение:
if(k%n == 0 || k%m == 0){
    console.log('yes');
}
else{
    console.log('no');
}
//------------------------------------------------------------------------------------------------------------
============dz_2=============
