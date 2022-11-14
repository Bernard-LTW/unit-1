# Quiz 013

## Prompt
Create a function that recieves one input and produces the output shown below.

Example: Input 2,6 Output 8

Example: Input 4,10 Output 34

Example: Input 10,10 Output 90

Example: Input 70,50 Output 3480

## Flow Diagram
![](Quiz013_FlowDiagram2.jpg)

*Fig.1* **Flow diagram of the program**


## Code Structure 
```.py
#2022-09-30 Quiz 013
#Create a function that recieves one input and produces the output shown below.
#Example: Input 2,6 Output 8
#Example: Input 4,10 Output 34
#Example: Input 10,10 Output 90
#Example: Input 70,50 Output 3480

def mystery(n, m):
    if abs(n-m) == 0:
        return int((n*m)-n)
    else:
        return int((n*m)-abs(n-m))

print(mystery(int(input("Enter a number: ")), int(input("Enter a number: "))))
```

## Evidence
![](Quiz013_Evidence.jpg)

*Fig.2* **Screenshot showing the result of the program**

![](Quiz013_Evidence2.jpg)

*Fig.3* **Screenshot showing the result of the program**

![](Quiz013_Evidence3.jpg)

*Fig.4* **Screenshot showing the result of the program**

![](Quiz013_Evidence4.jpg)

*Fig.5* **Screenshot showing the result of the program**
