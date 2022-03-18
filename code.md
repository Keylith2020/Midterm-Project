import math
numbers =[6,5,3,8,4,2,5,4,11,43,1,17,27,90,77,62,51,47,82,86,20]
e = 0
while(e<len(numbers)):
    print(numbers[e])
    print("index item with number",e,":",numbers[e])
    e = e+1

print("Now we will print every other number with index represented")
total = 0
for ele in range(0, len(numbers)):
    total = total + numbers[ele]
for count in range(0,len(numbers),2):
    print("Index Number",count,":",numbers[count])

average = total / len(numbers)    
print("The sum of all the numbers is: ", total)
print("The average is: ", average)
print(" he amount of numbers in the list is",(len(numbers)))