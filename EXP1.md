# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 16-8-24                                                                                                                                                     
### REGISTER NUMBER : 212221040135

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

```
###do...while:
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        if start > 0 and end > 0: 
            while start <= end:   
                print(start, end=' ')
                start += 1
        else:
            print("Both START and END should be positive numbers.")
    else:
        print("Enter a valid positive number.")

display()

###while...do:
start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    if start > 0 and end > 0:
        while start < end:
            print(start)
            start += 1
    else:
        print("Enter a valid positive number.")
else:
    print("Enter a valid positive number.")

###if...else:
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")

    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()


##switch:
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")
switch()

###for:
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()

```

### Output:
![do…while](https://github.com/user-attachments/assets/cddc8a53-d9a0-45a0-aaeb-2ea840a6c82d)
![while…do](https://github.com/user-attachments/assets/0ceaf8c1-4615-4278-a7e0-6560aba8285b)

![if else](https://github.com/user-attachments/assets/adf29a65-0fb9-437c-88a3-8f9111b8db34)
![switch](https://github.com/user-attachments/assets/251cd3ab-4c5e-4f48-a2e6-0e3318dcd3a8)
![for](https://github.com/user-attachments/assets/fa259510-959c-4d4a-90d5-c44cf4ce6509)




### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


