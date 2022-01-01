from random import *
num = randint(1,100)
print('Добро пожаловать в числовую угадайку')

def is_valid(s):
    return s.isdigit() and 1 <= int(s) <= 100
while True:
    print('введите предполагаемое число от 1 до 100')
    s=input()
    if is_valid(s) == False:
        print('А может быть все-таки введем целое число от 1 до 100?')
        continue
    else:
        s=int(s)
    if s < num :
        print('Ваше число меньше загаданного, попробуйте еще разок')
    elif s > num :
        print('Ваше число больше загаданного, попробуйте еще разок')
    elif s ==  num:
        print('Вы угадали, поздравляем!')
        break

print('Спасибо, что играли в числовую угадайку. Еще увидимся...')
