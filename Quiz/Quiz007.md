# Quiz 007

## Prompt
Create a program that create 10 random passwords with digits and letters of length 20

For HL :  Ask the user for the length and if symbols should be included

## Code Structure 
```.py
#2022-09-15 Quiz 007

# Prompt : Create a program that create 10 random passwords with digits and letters of length 20
# For HL :  Ask the user for the length and if symbols should be included

# Importing Libraries
import random

# Initialize Variables
passwords = []
Danger = [58, 59, 60, 61, 62, 63, 64, 91, 92, 93, 94, 95, 96, 123, 124, 125, 126]
password = ""
length = int(input("Input desired length of password: "))
symbols = input("Include symbols? (True/False): ")

# Main Program
for i in range(10):
    for i in range(length):
        if symbols == "True":
            temp = random.randint(33, 126)
            while temp in Danger:
                temp = random.randint(33, 126)
            password += chr(temp)
        else:
            temp = random.randint(48, 126)
            while temp in Danger:
                temp = random.randint(48, 126)
            password += chr(temp)
    passwords.append(password)
    password = ""

# Print Output
print("\n".join(passwords))

## End of Program ##
```

## Evidence
![](Quiz007_Evidence.jpg)
*Fig.1* **Screenshot showing the result of the program**
