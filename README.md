# task1: check even or odd
num=int(input("enter number: "))
if num%2==0:
    print("even")
else:
    print("odd")


# task2: sum of first 50 integers
total = 0
for i in range(1, 51):
    total += i
    print(i)
print("sum of first 50 integers is:", total)
