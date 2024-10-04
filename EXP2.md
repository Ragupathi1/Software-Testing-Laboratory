# Ex.No: 2   Matrix Multiplication 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:
```
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
```












### Output:
 

![stl-2 output](https://github.com/user-attachments/assets/f69e915a-612e-4b72-9f3d-e5e04be54aa9)




### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

