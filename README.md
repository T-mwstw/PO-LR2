# PO-LR2

Задача 4.5 (Семья Вито)
PC/UVaIDs:  110401/10041
Знаменитый гангстер Вито Дедстоун переезжает в Нью-Йорк. У него там очень большая семья, и все живут на Лямафия-авеню. Так как он собирается навещать всех своих родственников очень часто, он хочет найти дом рядом с ними.
На самом деле Вито хочет свести к минимуму совокупное расстояние до всех своих родственников, и он шантажирует вас с целью заставить написать программу, которая решит его проблему.
Входные данные
Входные данные состоят из нескольких тестовых блоков. Первая строка содержит число тестовых блоков.
В каждом тестовом блоке вам будет задано целое число родственников r
(0 < r < 500) и номера домов (также целые числа) s1, s2..... si.....sr, в которых они
проживают. Несколько родственников могут жить в одном доме.

Выходные данные
Для каждого тестового блока ваша программа должна вывести минимальную сумму расстояний от оптимального дома Вито до домов всех его родственников. Расстояние между двумя домами с номерами si, и sj вычисляется по формуле
dij = | Si—Sj|.

Пример входных данных
2
2   2  4
3   2   4   6
Соответствующие выходные данные
2 4
