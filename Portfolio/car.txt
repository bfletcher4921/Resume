

class Car:
    '''
    objects instantiated from this calss represents specific cars.
    '''
    def __init__(self):
        self.make = ''
        self.model = ''
        self.year = 0
        
if __name__ == "__main__":
    c1 = Car()
    c1.make = "Ford"
    c1.model = "Mustang"
    c1.year = 1968
    
    #test attributes
    assert(c1.make == "Ford"),"wrong make"
    print(f'my car is a {c1.make} {c1.model} from {c1.year}')