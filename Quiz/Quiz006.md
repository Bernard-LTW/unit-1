# Quiz 006(Unfinished

## Prompt
Given a string, create a program that produces the sum of the charcter in the string

## Code Structure 
```.py
#022-09-13 Quiz 006
#Prompt : Given a string, create a program that produces the sum of the charcter in the string

string = input("Input a string: ")
sum = 0
for char in string:
    sum += ord(char)

sum = sum - 96*len(string)
print(sum)
```

## Evidence
![](Quiz006_Evidence.jpg)
*Fig.1* **Screenshot showing the result of the program**
