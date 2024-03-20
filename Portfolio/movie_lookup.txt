# TODO: insert all comment blocks (see homework_program.py)
# Author: Brandi Fletcher
# Section: CIS 225 01 
# Date: 11/9/2023
# File: movie_lookup.py


# populate the list with the text from the file with the 
# given filename
def read_file(filename):
    f = open(filename, 'r')
    title_list = f.readlines()
    f.close()
    return title_list

# return the first movie, from the provided list of titles, that 
# begins with the letters in the search pattern provided
def find_movie(title_list, pattern):
    
    for title in title_list:
        if title.startswith(pattern):
            return title 
    

def main():
    
    filename = "movie_titles.txt"
    # create an empty list for movies
    title_list = []
    # call the function to read the txt file and populate the list
    title_list = read_file(filename)
    # prompt the user to: 
    # Enter the pattern to search or ['quit']:
    pattern = input("Enter pattern to search or ['quit']: ")
    while pattern != 'quit':
        output = find_movie(title_list, pattern)
        print (output)
        pattern = input("Enter pattern to search or ['quit']: ")
    # call the function to return a movie title so that we can
    # show it to the end user
    
main()
'''if __name__ == '__main__':
    pass
    # write your functions first!
    # use code here to test your functions individually'''
