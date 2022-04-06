# Alikhan-ict
count1 = 0
count2 = 0
for i in range(10):
    num = int(input())
    if num > 10:
        count1 = count1 + 1
    if num == 0:
        count2 = count2 + 1
print('Было введено', count1, 'чисел, больших 10.')
print('Было введено', count2, 'нулей.' )
