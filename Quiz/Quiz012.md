# Quiz 012

## Prompt
Create a function that reviebes integer 2<n<10, and returns the multiplication table of that number up to 9.

## Flow Diagram
![](Quiz012_FlowDiagram.jpeg)

*Fig.1* **Flow diagram of the program**

## Code Structure 
```.py
#2022-09-27 Quiz 012

#Create a function that reviebes integer 2<n<10, and returns the multiplication table of that number up to 9.

#Example: mulTable(2) returns "2 x 1 = 2
def mulTable(n, temp=""):
    for i in range(1,10):
        temp += f"{n} x {i} = {n*i}\n"

    return temp

print(mulTable(int(input("Enter a number: "))))

## End of Program##
```

## Evidence
![](Quiz012_Evidence.jpg)
*Fig.2* **Screenshot showing the result of the program**
