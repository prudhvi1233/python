# python
#Print numbers from 1 to 30, but break the loop when the number is divisible by both 4 and 7.


for i in range(1, 31):
    if i % 4 == 0 and i % 7 == 0:
        break
    print(i)
