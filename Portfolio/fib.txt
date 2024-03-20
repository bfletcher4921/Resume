#prompt for N
n = int(input("Enter a length of the series: "))
if n < 1:
    print("invalid input")
    exit()

fib = [1, 1]

#calculate fib series to n elements
while len(fib) < n:
     i = len(fib)
     fib.append(fib[i-1] + fib[i-2])

     
print(fib)     
