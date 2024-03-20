m = int(input('enter an integer: '))
n = int(input('enter an integer: '))
r = -1
while r != 0  :
#find remainder
    r = m % n

#is remainder zero
    if r == 0:
        print(n)
    else:
        m = n
        n = r
    