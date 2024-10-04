### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:

1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:

```
num = input("Enter a number: ")
flag = 0

if num.isnumeric():
    z = int(num)
    
    if z == 2:
        flag = 1
    elif z > 2:
        for i in range(2, z//2 + 1):
            if z % i == 0:
                flag = 0
                break
        else:
            flag = 1
    
    if flag == 1:
        print("Prime Number")
    else:
        print("Not a Prime Number")
else:
    print("Enter a Positive Number")
```











### Output:

![stl-5 output](https://github.com/user-attachments/assets/dc0099c5-693d-4de7-a1c6-74c6fd09947a)


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.

