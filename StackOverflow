import sys
import csv
import numpy as np


def Main():
    login()


def login():
	
    with open('MatrixAccess.csv') as csvfile: #I import the csv file
	    reader = csv.reader(csvfile, delimiter = ';') #I read through it
	    x = list(reader) # I convert the csv into an array to loop through it easier with the numpy library
    print(np.matrix(x)) #I print it to check if I imported it correctly
    print("Username: ")
    str1 = input()
    print("Password: ")
    str2 = input()
    for i in [2]:
            for j in [i]: #I have to convert the ints to lists so I can iterate through the list
        	    if(str1 == x[i][j] and str2 == x[i][j+1]):
        		    print("Access granted")
        	    else:
        		    print("Access not granted")

def menu():
    print("************MAIN MENU**************")







#We initiate the program
Main()
