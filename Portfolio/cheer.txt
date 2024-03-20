

'''def cheer(num, phrase):
    for i in range (num):
        print(phrase)
cheer(10, "roar lions")
cheer(3, "trash pandas")
'''

def mascot_cheer(num, verb, mascot):
    for i in range (num):
        print(verb, mascot)
    return "hello"
        
'''mascot_cheer(3, "Roar", "Lions")
mascot_cheer(3, "Moo", "Bisons")
mascot_cheer(3, "cumple", "Lions")
'''

def main():
    asun = {"Lions" : "roar", "Bisons" : "moo", "hatters" : "crumple", "dolphins" : "squeak"}
    
    for mascot in asun:
        var = mascot_cheer(3, asun[mascot], mascot)
        print(var)
main()
