# Author: Brandi Fletcher
# Section: CIS 225 01 
# Date: 9/29/23
# File: letter_grade.py 
#
# prompts the user for their numeric grade and then displays the corresponding letter grade
#A90 - 100%
#B80 - 89%
#C70 - 79%
#D60 - 69%
#FLess than 60%

def main():
    
    try:
        score = float(input("Enter your numeric grade: "))
    except ValueError as score:
        print("You must enter a number.")
        
    else:
        
    
        if score < 0 or score > 100:
            print("invalid value")
    
        elif score >= 90:
            print("A")
        elif score >= 80:
            print("B")
        elif score >= 70:
            print("C")
        elif score >= 60:
            print("D")
        else:
            print("F")
        
main()
