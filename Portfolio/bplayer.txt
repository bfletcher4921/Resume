# Author: Brandi Fletcher
# Section: CIS 225 01 
# Date: 11/16/23
# File: bplayer.py
#
# Create a BaseballPlayer class. Your class needs to have attributes 
#for name, jersey number, and position. Be sure to initialize numeric 
#attributes to zero and string attributes to the empty string

class BaseballPlayer:
    '''
    objects instantiated from this calss represents specific cars.
    '''
    def __init__(self):
        self.name = ''
        self.jersey_number = 0
        self.position = ''