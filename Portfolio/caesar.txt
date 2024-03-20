# Author: Brandi Fletcher
# Section: CIS 225 01 
# Date: 9/14/23
# File: caesar.py (change to correct name)
#
# A I/O program that creates a cipher from a 15 character phrase using ASII and shift

def main():
    #input
    phrase = input("Enter the 15 character phrase to be encrypted: ")
    shift = int(input("Enter the shift factor: "))
    #processing
    
    c0 = ord(phrase[0]) + shift
    c1 = ord(phrase[1]) + shift
    c2 = ord(phrase[2]) + shift
    c3 = ord(phrase[3]) + shift
    c4 = ord(phrase[4]) + shift
    c5 = ord(phrase[5]) + shift
    c6 = ord(phrase[6])+ shift
    c7 = ord(phrase[7]) + shift
    c8 = ord(phrase[8]) + shift
    c9 = ord(phrase[9]) + shift
    c10 = ord(phrase[10]) + shift
    c11 = ord(phrase[11]) + shift
    c12 = ord(phrase[12]) + shift
    c13 = ord(phrase[13]) + shift
    c14 = ord(phrase[14]) + shift
    
    message_tuple = (c0, c1, c2, c3, c4, c5, c6, c7, c8, c9, c10, c11, c12, c13, c14)
    #output
    print (message_tuple)
    

main()
