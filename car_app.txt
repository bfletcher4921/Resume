from car import Car

def main():
    classic = Car()
    classic.make = "Ford"
    classic.model = "Model A"
    classic.year = 1929
    
    muscle = Car()
    muscle.make = "Pontiac"
    muscle.model = "GTO"
    muscle.year = 1964
    
    ev = Car()
    ev.make = "Tesla"
    ev.model = "Model 3"
    ev.year = 2023

    #single list
    cars = [classic, muscle, ev]
    for car_obj in cars:
    
        print (f'{car_obj.make} {car_obj.model} from {car_obj.year}')    

main()