#prompt for N
n = int(input("Enter a positive integer: "))
if n <= 1:
    print("invalid input")
    exit()

total = 1

#calculate n!
while n > 0:
     total = total * n
     n -= 1
print(total)     
