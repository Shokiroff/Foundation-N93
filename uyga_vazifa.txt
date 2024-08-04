1.
import random as rd
def split_list(lst, n):
    return [lst[i:i + n] for i in range(0, len(lst), n)]
lst = [rd.randint(10,50) for x in range(10)]
n = int(input("Sonni kirit>>> "))
natija = split_list(lst, n)
print(natija)


3.import random as rd
def count_elements(myList):
    myDct = {}
    for element in myList:
        if element in myDct:
            myDct[element] += 1
        else:
            myDct[element] = 1
    return myDct

myList = [rd.randint(10,20) for x in range(10)]
print("Saralashdan oldin", myList)
myDct = count_elements(myList)
print("Saralangandan kn ",myDct)


4.
cars= [
	{"mode1":"RDX":"year":2009},
	{mode1":"LS":"year":2010}
sorted_cars=sorted(cars,key=lambda x :x['year'])
print(sorted_cars)
