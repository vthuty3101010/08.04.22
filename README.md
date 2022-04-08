Задание 1
print(len(set(map(int, input() .split())))) #разбивает строки на подстроки

Задание 2
print(len(set(input().split()) & set(input().split())))

Задание 3
print (*sorted(set(input() .split()) & set(input() .split()) , key=int))
