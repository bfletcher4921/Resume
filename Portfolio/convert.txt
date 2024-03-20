def get_bs():
#input
    bolivars = int(input("Enter the number of Bs: "))
    return bolivars

def to_dollars(b):
    dollars = b / 25
    return dollars

def display(bolivars, dollars):
    print(f'{bolivars} Bs. is ${dollars:.2f}')

def main():

    #input
    b = get_bs()
    
    #processing
    d = to_dollars(b)

    #output
    display(b,d)

main()