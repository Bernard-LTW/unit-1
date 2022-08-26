### Basic Base Converter(Array v1)
## Introduction

This is a basic base converter that converts a positive integer from Base 10 to Base 2-9 inclusive with an array written in python


```.py

#2022-08-25 - Base Converter
#This program converts a positive integer from Base 10 to Base 2-9 inclusive with an array.

#Initizalize variables
orig_num = int(input("Input the positive number you want to convert: "))
base = int(input("Input the base you want to convert to from 2 to 9: "))
output_storage = []

#Check for invalid base
if base < 3 or base > 10:
    print("Base must be from 2 to 9 inclusive")
    exit()

#Main calculation
div = int(orig_num/base)
mod = orig_num % base
output_storage.append(mod)

while div > base-1:
    mod = int(div%base)
    div = int(div/base)
    output_storage.append(mod)

output_storage.append(div)

#Print output
output_storage.reverse()
print(output_storage)

##End of program##

```
## Test results
