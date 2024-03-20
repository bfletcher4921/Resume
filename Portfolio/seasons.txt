month = input()
day = int(input())


if month == "March" and (day >= 20 and day <= 31) :
    print ("Spring")
elif month == "April" and (day >= 1 and day <=30):
    print("Spring")
elif month == "May" and (day >= 1 and day <=30):
    print ("Spring")
elif month == "June" and (day >= 1 and day <= 20):
    print("Spring")
    
elif month == "June" and (day >= 21 and day <= 22):
    print ("Summer")
elif month == "July" and (day >= 1 and day <=31) :
    print ("Summer")
elif month =="August" and (day >= 1 and day <=30):
    print ("Summer")
elif month == "September" and (day >=1 and day <=21):
    print ("Summer")
elif month == "September" and( day >= 22 and day <=30):
    print ("Autumn")
elif month == "October" and (day >= 1 and day <=31):
    print ("Autumn")
elif month == "November" and (day >=1  and day <= 30):
    print ("Autumn")
elif month == "December" and (day >= 1 and day <= 20):
    print ("Autumn")
elif month == "December" and (day >= 20 and day <= 31):
    print ("Winter")
elif month == "January" and (day >= 1 and day <=31):
    print ("Winter")
elif month == "February" and (day >= 1 and day <=28):
    print ("Winter")
elif month == "March" and (day >= 1 or day <= 19):
    print ("Winter")

else: 
    print("Invalid")