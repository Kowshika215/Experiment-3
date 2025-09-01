# Experiment-3
## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
```
num = input("Enter a number: ")  
flag = 0  
if num.isnumeric():  
    z = int(num)  
    if z == 2:  
        flag = 1  
    elif z > 2:  
        for i in range(2, z // 2 + 1):  # Loop should include z//2
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

## Output

<img width="294" height="49" alt="Screenshot 2025-09-01 104915" src="https://github.com/user-attachments/assets/db0bd284-0dd8-43ac-bbbb-10278e416afa" />

<img width="286" height="48" alt="Screenshot 2025-09-01 104947" src="https://github.com/user-attachments/assets/ed6d46fa-cc0c-4e6a-a297-1fa6fafd20ce" />

<img width="450" height="51" alt="Screenshot 2025-09-01 105101" src="https://github.com/user-attachments/assets/0cc85599-f64a-4451-826f-cd5f66eb6792" />

<img width="362" height="56" alt="Screenshot 2025-09-01 105017" src="https://github.com/user-attachments/assets/ff7b2c1c-6002-4e73-8506-777bf12a6ccc" />


## Result

Thus,to write a python program to check the number is prime or not and inspect for failures is verified successfully.
