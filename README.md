# 1_modul
# 1. Напишите код, который создает переменную `name` и присваивает ей строковое значение. Затем выведите значение переменной на экран.
name = 'Sofisky'
print(name)
# 2. Создайте список из трех элементов и измените второй элемент на новое значение. Напечатайте измененный список.
laptop = ['HP','Dell','Mac']
laptops[1] = 'mac'
print(laptops)
# 3. Напишите код, который вычисляет сумму двух чисел и выводит результат на экран.
a = int(input())
b = int(input())
c = a+b
print(c)
#5. Напишите функцию, которая принимает два числа и возвращает их произведение.
def multiply(a, b):
    return a * b

result = multiply(4, 5)
print(result)
#6. Используя цикл `for`, создайте код, который выводит числа от 1 до 10 на одной строке, разделенные пробелом.
numbers = list(range(1,11))
for number in numbers:
    print(number, end=' ')
#7. Напишите код, который создает словарь с тремя ключами и значениями, и затем изменяет значение одного из ключей.
laptop_0 = {'model':'HP",'apiratifka':8}
laptop_0['apiratifka'] = 16
print(laptop_0)
#8. Создайте кортеж с 4 элементами и напечатайте его длину.
laptop_0 = ['hp','dell','mac']
uzunlik = len(car_0)
print(uzunlik)
#9. Используя цикл `while`, напишите код, который выводит числа от 10 до 1 в обратном порядке.
son = 10
while son >= 1:
    print(son, end= ' ')
    son = son - 1
#10. Напишите функцию, которая принимает список чисел и возвращает список, содержащий только четные числа.

son = list(range(2,100,2))
print(son)

#11. Используя метод `.split()`, разделите строку на слова и напечатайте каждое слово на новой строке.
turlar = 'canon hp '
ruyxat = turlar.split(" ")
for i in ruyxat:
    print(i)
#12. Напишите код, который создает пустое множество и добавляет в него три элемента.
odam = []
odam.append('Bekzod')
odam.append('Sherzod')
odam.append('Ozod')

print(odam)


#15. Напишите функцию, которая принимает строку и возвращает строку, перевернутую задом наперед.

numbers = [25,15,815,525,163,682,5,9,940,75]
numbers.sort()
print(numbers)

#16. Используя функцию `range()`, напишите код, который создает список из первых 5 квадратов чисел (1, 4, 9, 16, 25).

sonlar = list(range(1,6))
kvadrati = []
for i in sonlar:
    i = i*i
    kvadrati.append(i)
print(kvadrati)

#17. Напишите код, который проверяет, является ли число положительным, отрицательным или нулем, и выводит соответствующее сообщение.


son = float(input('sonni kiring = '))
if son > 0:
    print('kiritilgan son musbat')
elif son == 0:
    print('bu son nolga teng')
elif son < 0:
    print('bu son manfiy son')


#



