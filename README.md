## Python-Task-s-Submission-s-UpskilTutedude-Assignment-2
# Task 1: Check if a Number is Even or Odd
**filename**:`task1`
# Problem Statement:  
Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.
Expected Output:
The program should return an output like:
# sample input:
Enter a number: 7
# sample output:
7 is an odd number
# Task 2: Sum of Integers from 1 to 50 Using a Loop
**filename**:`task1`
# Problem Statement: 
Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.
Expected Output:
The program should return:
# sample output:
The sum of numbers from 1 to 50 is: 1275
# task1
```python
n=int(input("Enter a number: "))
if n%2==0:
    print(f"{n} is an even number.")
else:
    print(f"{n} is an odd number.")
```
# task2
```python
c=0
for i in range(1,51):
    c+=i
print(f"The sum of numbers from 1 to 50 is: {c}")
```
# How to Run
```bash
Make sure you have Python installed. Then run each script using:
python task1.py
python task2.py




