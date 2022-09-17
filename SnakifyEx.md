# Snakify Exercises
## Chapter 1: Input, print and numbers

### Sum of three numbers
```.py
a = int(input())
b = int(input())
c = int(input())
print(a + b + c)
```
![](SnakifyAssets/1.1.jpg)

### Hi John
```.py
a = input()
b = "Hi"
print(b,a)
```
![](SnakifyAssets/1.2.jpg)

### Square
```.py
a = int(input())
print (a**2)
```
![](SnakifyAssets/1.3.jpg)

### Area of right-angled triangle
```.py
b = int(input())
h = int(input())
print(b*h/2)
```
![](SnakifyAssets/1.4.jpg)

### Hello, Harry!
```.py
name = input()
print('Hello,', name+"!")
```
![](SnakifyAssets/1.5.jpg)

### Apple sharing
```.py
n = int(input())
k = int(input())
print(k // n)
print(k % n)
```
![](SnakifyAssets/1.6.jpg)

### Previous and next
```.py
a = int(input())
print("The next number for the number",a,"is", a+1.)
print("The previous number for the number",a,"is", a-1.)
```
![](SnakifyAssets/1.7.jpg)

### Two timestamps
```.py
h1 = int(input())
m1 = int(input())
s1 = int(input())
h2 = int(input())
m2 = int(input())
s2 = int(input())

final1 = h1*60*60+m1*60+s1
final2 = h2*60*60+m2*60+s2

print(final2-final1)
```

![](SnakifyAssets/1.8.jpg)

### School desks
```.py
a = int(input())
b = int(input())
c = int(input())

if (a % 2) != 0:
    a=a+1
a=a/2
if (b % 2) != 0:
    b=b+1
b=b/2
if (c % 2) != 0:
    c=c+1
c=c/2
    
final = a+b+c
print(final)
```
![](SnakifyAssets/1.9.jpg)

## Chapter 2: Integer and float numbers

### Last digit of integer
```.py
a = int(input())
print(a%10)
```
![](SnakifyAssets/2.1.jpg)


### Two digits
```.py
a = int(input())
aanswer = a%10 
a = a//10
print(a, aanswer)
```

![](SnakifyAssets/2.2.jpg)

### Swap digits
```.py
a = int(input())
aanswer = a%10 
a = a//10
a = str(a)
aanswer=str(aanswer)
print(aanswer+a)
```

![](SnakifyAssets/2.3.jpg)

### Last two digits
```.py
a=int(input())
print(a%100)
```
![](SnakifyAssets/2.4.jpg)

### Tens digit
```.py
number = int(input("Input an integer: "))
number = number//10
answer = number%10 
print(answer)
```
![](SnakifyAssets/2.5.jpg)

### Sum of digits
```.py
a=int(input())
print((a//100)+((a%100)//10)+((a%100)%10))
```
![](SnakifyAssets/2.6.jpg)

### Reverse three digits
```.py
a = int(input())
b = (a//100)
c = ((a%100)//10)
d = ((a%100)%10)
b=str(b)
c=str(c)
d=str(d)
print(d+c+b)
```
![](SnakifyAssets/2.7.jpg)

### Merge two numbers
```.py
a = int(input())
b = int(input())

a1 = (str(a//10))
a2 = (str(a%10))
b1 = (str(b//10))
b2 = (str(b%10))

print(a1+b1+a2+b2)
```

![](SnakifyAssets/2.8.jpg)

### Cyclic rotation
```.py
num = int(input())
res = [int(x) for x in str(num)]
print(str(res[2])+str(res[3])+str(res[0])+str(res[1]))
```
![](SnakifyAssets/2.9.jpg)

### Fractional Part
```.py
a = float(input())
b = int(a)
a=a-b
print(a)
```

![](SnakifyAssets/2.10.jpg)

### First digit after decimal point
```.py
b = float(input())
a = (int((b*10)%10))
print(a)
```
![](SnakifyAssets/2.11.jpg)

### Car route
```.py
from math import ceil

n = int(input())
m = int(input())
print(ceil(m/n))
```
![](SnakifyAssets/2.12.jpg)

### Day of week
```.py
a = int(input())
a=a+3
a=a%7
print(a)
```

![](SnakifyAssets/2.13.jpg)

### Digital clock
```.py
N = int(input())
print(N//60, N%60)
```

![](SnakifyAssets/2.14.jpg)

### Total cost
```.py
a = int(input())
b = int(input())
c = int(input())

print(((a*c)+b*c//100),((b*c)%100))
```

![](SnakifyAssets/2.15.jpg)

### Century
```.py
a = int(input())
if a%100 == 0:
    print(a//100)
else:
    print(a//100+1)
```

![](SnakifyAssets/2.16.jpg)

### Snail
```.py
from math import ceil

h = int(input())
a = int(input())
b = int(input())
print(ceil((h - a) / (a - b)) + 1)
```
![](SnakifyAssets/2.17.jpg)

### Clock face - 1
```.py
h = int(input())
m = int(input())
s = int(input())

print(h * 30 + m * 30 / 60 + s * 30 / 3600)
```
![](SnakifyAssets/2.18.jpg)

### Clock face - 2
```.py
a = float(input())
a = (a%30)*12
print(a)
```

![](SnakifyAssets/2.19.jpg)

## Chapter 3: Conditions: if, then, else

### Is Positive
```.py
a = int(input())
if a >= 0:
    print("YES")
else:
    print("NO")
```
![](SnakifyAssets/3.1.jpg)

### Is odd
```.py
a = int(input())

if a%2 != 0:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.2.jpg)

### Is even
```.py
a = int(input())

if a%2 == 0:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.3.jpg)

### Ends on seven
```.py
a = int(input())
if a%10 == 7:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.4.jpg)

### Minimum of two numbers
```.py
a = int(input())
b = int(input())

if a<b:
    print(a)
else:
    print(b)
```

![](SnakifyAssets/3.5.jpg)

### Are both odd
```.py
a = int(input())
b = int(input())

if a%2 != 0 and b%2 != 0:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.6.jpg)

### At least one odd
```.py
a = int(input())
b = int(input())

if a%2 != 0 or b%2 != 0:
    print("YES")
else:
    print("NO")
```
![](SnakifyAssets/3.7.jpg)

### Exactly one odd
```.py
a = int(input())
b = int(input())

if a%2 != 0 and b%2 == 0:
    print("YES")
elif a%2 == 0 and b%2 != 0:
    print("YES")
else:
    print("NO")
```
![](SnakifyAssets/3.8.jpg)

### Sign function
```.py
a = int(input())

if a == 0:
    print("0")
elif a>0:
    print("1")
else:
    print("-1")
```

![](SnakifyAssets/3.9.jpg)

### Numbers in ascending order
```.py
a = int(input())
b = int(input())
c = int(input())

if a<b<c :
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.10.jpg)

### Is three digits
```.py
a = int(input())

if 99<a<1000:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.11.jpg)

### Minimum of three numbers
```.py
a = int(input())
b = int(input())
c = int(input())

if b >= a <= c:
    print(a)
elif a >= b <= c:
    print(b)
else:
    print(c)
```

![](SnakifyAssets/3.12.jpg)

### Equal numbers
```.py
a = int(input())
b = int(input())
c = int(input())
if a == b == c:
    print(3)
elif a == b or b == c or a == c:
    print(2)
else:
    print(0)
```

![](SnakifyAssets/3.13.jpg)

### Rook move
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
if x1 == x2 or y1 == y2:
    print('YES')
else:
    print('NO')
```

![](SnakifyAssets/3.14.jpg)

### Chess board - black square
```.py
column = int(input())
row = int(input())

if row % 2 == column % 2:
    print('BLACK')
else:
    print('WHITE')
```

![](SnakifyAssets/3.15.jpg)

### Chess board - same color
```.py
column = int(input())
row = int(input())
column1=int(input())
row1=int(input())

if (row+column+row1+column1)%2==0:
    print('YES')
else:
    print('NO')
```

![](SnakifyAssets/3.16.jpg)

### Distance to the cloest point
```.py
a = int(input())
b = int(input())
c = int(input())

a_to_b = abs(a - b)
a_to_c = abs(a - c)

if a_to_b < a_to_c:
    print(a_to_b)
else:
    print(a_to_c)
```

![](SnakifyAssets/3.17.jpg)

### Digits in ascending order
```.py
a = int(input())


if a//100<(a%100-a%10)/10<a%10:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.18.jpg)

### Four-digit palindrome
```.py
num=int(input())
temp=num
rev=0
while(num>0):
    dig=num%10
    rev=rev*10+dig
    num=num//10
if(temp==rev):
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.19.jpg)

### King move
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
if x1 - x2 < 2 and y1 - y2 < 2 and x1 - x2 > -2 and y1 - y2 > -2 :
    print('YES')
else:
    print('NO')
```

![](SnakifyAssets/3.20.jpg)

### Bishop move
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
if x1 - x2 == y1 - y2 or x1 - x2 == y2 - y1:
    print('YES')
else:
    print('NO')
```

![](SnakifyAssets/3.21.jpg)

### Queen move
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
if x1 == x2 or y1 == y2 or x1 - x2 == y1 - y2 or x1 - x2 == y2 - y1:
    print('YES')
else:
    print('NO')
```

![](SnakifyAssets/3.22.jpg)

### Index of outlier
```.py
a = int(input())
b = int(input())
c = int(input())

if a==b!=c:
    print("3")
elif a==c!=b:
    print("2")
elif a!=b==c:
    print("1")
```

![](SnakifyAssets/3.23.jpg)

### Knight move
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())

if abs(x1-x2)==2 and abs(y1-y2)==1 or abs(x1-x2)==1 and abs(y1-y2)==2:
    print("YES")
else:
    print("NO")
```

![](SnakifyAssets/3.24.jpg)

### Chocolate bar
```.py
n = int(input())
m = int(input())
k = int(input())
if k <= n * m and (k % n == 0 or k % m == 0):
    print('YES')
else:
    print('NO')
```

![](SnakifyAssets/3.25.jpg)

### Leap year
```.py
a=int(input())
if a%4==0 and a%100!=0 or a%400==0:
    print("LEAP")
else:
    print("COMMON")
```

![](SnakifyAssets/3.26.jpg)

### Days in months
```.py
a = int(input())

if a == 1 or a == 3 or a == 5 or a == 7 or a == 8 or a == 10 or a == 12:
    print("31")
elif a == 4 or a == 6 or a == 9 or a == 11:
    print("30")
else:
    print("28")
```

![](SnakifyAssets/3.27.jpg)

### Next day
```.py
a = int(input())
b = int(input())
if b == 31:
    a = a+1
    b =1
elif b == 30:
    if a == 4 or a == 6 or a == 9 or a == 11:
        a = a+1
        b =1
    else: b = b+1
elif a==2 and b==28:
    a = a+1
    b =1
else:
    b = b+1

if a > 12:
    a = 1

print(a)
print(b)
```

![](SnakifyAssets/3.28.jpg)

### Linear equation
```.py
a = int(input())
b = int(input())

if a == 0 and b == 0:
    print("many solutions")
elif a == 0 or b == 0:
    print("no solution")

elif b%a != 0 or a == 0 or b == 0:
    print("no solution")
else:
    print(b/a)
```

![](SnakifyAssets/3.29.jpg)

### Vertices of rectangle
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
x3 = int(input())
y3 = int(input())

if x1 == x2:
    x4 =x3
elif x1 == x3:
    x4 = x2
else:
    x4 = x1

if y1 == y2:
    y4=y3
elif y1 == y3:
    y4 = y2
else:
    y4 = y1

print(x4)
print(y4)
```

![](SnakifyAssets/3.30.jpg)

### Sort three numbers
```.py
a = int(input())
b = int(input())
c = int(input())

if a > b:
    a , b = b , a
    
if a > c:
    a, c = c, a
if b > c:
    b, c = c, b

print(a)
print(b)
print(c)
```

![](SnakifyAssets/3.31.jpg)

### White pawn move
```.py
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
if abs(x1 - x2) < 2 and y1 > 1 and y1 < y2:
    if y2 - y1 < 2:
        print("YES")
    elif y1 == 2 and y2 - y1 < 3 and x1 == x2:
        print("YES")
    else:
        print("NO")
else:
    print("NO")
```

![](SnakifyAssets/3.32.jpg)

## Chapter 4: For loop with range

### Count to N
```.py
n = int(input())

for i in range(1,n+1):
    print(i)
```

![](SnakifyAssets/4.1.jpg)

### Series - 1
```.py
a = int(input())
b = int(input())

for i in range (a ,b+1):
    print(i)
```

![](SnakifyAssets/4.2.jpg)

### First N odd, ascending
```.py
a = int(input())

for i in range(1,a+1):
    if i%2 != 0:
        print(i)
```

![](SnakifyAssets/4.3.jpg)

### Series - 2
```.py
a = int(input())
b = int(input())

if a < b:
    for i in range(a,b+1):
        print(i)
else:
    for i in reversed(range(b,a+1)):
        print(i)
```

![](SnakifyAssets/4.4.jpg)

### First N even, descending
```.py
n = int(input())

for i in range(n,-1,-1):
    if i % 2 == 0:print(i)
```

![](SnakifyAssets/4.5.jpg)

### Sum of ten numbers
```.py
sum=0
for i in range(10):
    a = int(input())
    sum = sum + a
print(sum)
```

![](SnakifyAssets/4.6.jpg)

### Sum of N numbers
```.py
sum=0
n = int(input())
for i in range(n):
    a = int(input())
    sum = sum + a
print(sum)
```

![](SnakifyAssets/4.7.jpg)

### Product of N numbers
```.py
sum=1
n = int(input())
for i in range(n):
    a = int(input())
    sum = sum * a
print(sum)
```

![](SnakifyAssets/4.8.jpg)

### Sum of cubes
```.py
a = int(input())
sum=0
for i in range(a):
    sum=sum+(i+1)**3
print(sum)
```

![](SnakifyAssets/4.9.jpg)

### Factorial
```.py
a = int(input())
sum = 1
for i in range(2,a+1):
    sum = sum*i
print(sum)
```

![](SnakifyAssets/4.10.jpg)

### The number of zeros
```.py
n = int(input())
count = 0
for i in range(n):
    var = int(input())
    if var == 0:
        count = count+1
print(count)
```

![](SnakifyAssets/4.11.jpg)

### Adding factorials
```.py
n = int(input("n: "))
factorial = 1
result = 0

for x in range(n):
  x += 1
  factorial *= x
  result += factorial
  
print(result)
```

![](SnakifyAssets/4.12.jpg)

### Squares in range
```.py
a = int(input())
b = int(input())

for i in range(a,b+1):
    print(i,"*",i,"=",i*i,sep="")
```

![](SnakifyAssets/4.13.jpg)

### Ladder
```.py
n = int(input())
sum = ""
for i in range(1,n+1):
    sum = sum + str(i)
    print(sum)
```

![](SnakifyAssets/4.14.jpg)

### Is prime
```.py
num = int(input())
prime = False
if num > 1:
    for i in range(2, num):
        if (num % i) == 0:
            prime = True
            break
if prime:
    print("COMPOSITE")
else:
    print("PRIME")
```

![](SnakifyAssets/4.15.jpg)

### Print primes in range
```.py
a = int (input ())
b = int (input ())
for n in range(a, b + 1):
    is_prime = True
    for i in range(2, n - 1):
        if n% i == 0:
            is_prime = False
    if is_prime:
        print (n)
```

![](SnakifyAssets/4.16.jpg)

### Number of primes in range
```.py
a = int (input ())
b = int (input ())
count = 0
for n in range(a, b + 1):
    is_prime = True
    for i in range(2, n - 1):
        if n% i == 0:
            is_prime = False
    if is_prime:
        count = count + 1
print(count)
```

![](SnakifyAssets/4.17.jpg)

### Lost card
```.py
answer=0
N=int(input())
Original=N 
for i in range(N-1):
  N=int(input())
  answer+=N
for i in range(Original):
  Original+=i
  i+=N
Original-=answer
print(Original)
```
![](SnakifyAssets/4.18.jpg)

## Chapter 5: Strings

### Slices
```.py
n = input()
print(n[2])
print(n[-2])
print(n[:5])
print(n[:-2])
print(n[::2])
print(n[1::2])
print(n[::-1])
print(n[::-2])
print(len(n))
```
![](SnakifyAssets/5.1.jpg)

### The number of words
```.py
n = input()
print(n.count(' ') + 1)
```
![](SnakifyAssets/5.2.jpg)

### The two halves
```.py
s = input()
print(s[(len(s) + 1) // 2:] + s[:(len(s) + 1) // 2])
```
![](SnakifyAssets/5.3.jpg)

### To swap the two words
```.py
n = input()
print(n.split()[1], n.split()[0])
```
![](SnakifyAssets/5.4.jpg)

### The first and last occurrence
```.py
n = input()
if n.count('f') == 1:
    print(n.find('f'))
elif n.count('f') > 1:
    print(n.find('f'), n.rfind('f'))
```
![](SnakifyAssets/5.5.jpg)

### The second occurrence
```.py
n = input()
if n.count('f') == 1:
    print(-1)
elif n.count('f') == 0:
    print(-2)
else:
    print(n.find('f', n.find('f') + 1))
```
![](SnakifyAssets/5.6.jpg)

### Remove the fragment
```.py
n = input()
print(n[:n.find('h')] + n[n.rfind('h') + 1:])
```
![](SnakifyAssets/5.7.jpg)

### Reverse the fragment
```.py
n = input()
print(n[:n.find('h')] + n[n.rfind('h'):n.find('h'):-1] + n[n.rfind('h'):])
```
![](SnakifyAssets/5.8.jpg)

### Replace the substring
```.py
num = input()
print(num.replace('1', 'one'))
```
![](SnakifyAssets/5.9.jpg)

### Delete a character
```.py
str = input()
str = str.replace('@', '')
print(str)
```
![](SnakifyAssets/5.10.jpg)

### Replace within the fragment
```.py
s = input()
first = s.find('h')
last = s.rfind('h')
print(s[:first+1] + s[first+1:last].replace('h','H') + s[last:])
```
![](SnakifyAssets/5.11.jpg)

### Delete every third character
```.py
n = input()
for i in range(len(n)):
    if i % 3 != 0:
        print(n[i], end="")
```
![](SnakifyAssets/5.12.jpg)

##Chapter 6: While Loop

### List of squares
```.py
n = int(input())
i = 1
while i ** 2 <= n:
    print(i ** 2)
    i += 1
```
![](SnakifyAssets/6.1.jpg)

### Least divisor
```.py
n = int(input())
i = 2
while n % i != 0:
    i += 1
print(i)
```
![](SnakifyAssets/6.2.jpg)

### The power of two
```.py
n = int(input())
x = 0
while 2 ** x <= n:
    x += 1
print(x - 1, 2 ** (x - 1))
```
![](SnakifyAssets/6.3.jpg)

### Morning jog
```.py
a = int(input())
b = int(input())
i = 1
while a < b:
    i += 1
    a = a * 1.1
    
print(i)
```
![](SnakifyAssets/6.4.jpg)

### The length of the sequence
```.py
n = int(input())
count = 0
while n != 0:
    n = int(input())
    count += 1
print(count)
```
![](SnakifyAssets/6.5.jpg)

### The sum of the sequence
```.py
count = 0
sum = 0
while True:
    num = int(input())
    if num == 0:
        print(sum)
        break
    else:
        sum += num
        count += 1
```
![](SnakifyAssets/6.6.jpg)

### The average of the sequence
```.py
sum = 0
count = 0
element = int(input())
while element != 0:
    sum += element
    element = int(input())
    count += 1
    
print(sum/count)
```
![](SnakifyAssets/6.7.jpg)

### The maximum of the sequence
```.py
n = int(input())
max = n
while n != 0:
    if n > max:
        max = n
    n = int(input())
print(max)
```
![](SnakifyAssets/6.8.jpg)

### The index of the maximum of a sequence
```.py
n = int(input())
i = 0
max = 0
index = 0
while n != 0:
    if n > max:
        max = n
        index = i +1
    n = int(input())
    i += 1
print(index)
```
![](SnakifyAssets/6.9.jpg)

### The number of even elements of the sequence
```.py
n = int(input())
count = 0
while n != 0:
    if n % 2 == 0:
        count += 1
    n = int(input())
print(count)
```
![](SnakifyAssets/6.10.jpg)

### The number of elements that are greater than the previous one
```.py
n = int(input())
count = 0
while n != 0:
    m = n
    n = int(input())
    if n > m:
        count += 1
print(count)
```
![](SnakifyAssets/6.11.jpg)

### The second maximum
```.py
n = int(input())
max = 0
max2 = 0
while n != 0:
    if n > max:
        max2 = max
        max = n
    elif n > max2:
        max2 = n
    n = int(input())
print(max2)
```
![](SnakifyAssets/6.12.jpg)

### The number of elements equal to the maximum
```.py
n = int(input())
max = n
count = 0
while n != 0:
    if n > max:
        max = n
        count = 1
    elif n == max:
        count += 1
    n = int(input())
print(count)
```
![](SnakifyAssets/6.13.jpg)

### Fibonacci numbers
```.py
n = int(input())
if n == 0:
    print(0)
else:
    a, b = 0, 1
    for i in range(2, n + 1):
        a, b = b, a + b
    print(b)
```
![](SnakifyAssets/6.14.jpg)

### The index of a Fibonacci number
```.py
n = int(input())
a = 0
b = 1
c = 0
count = 1
while c < n:
    c = a + b
    a = b
    b = c
    count += 1
if c == n:
    print(count)
else:
    print(-1)
```
![](SnakifyAssets/6.15.jpg)

### The maximum number of consecutive equal elements
```.py
n = int(input())
max = 1
count = 1
while n != 0:
    n1 = int(input())
    if n == n1:
        count += 1
        if max < count:
            max = count
    else:
        count = 1
    n = n1
print(max)
```
![](SnakifyAssets/6.16.jpg)

## Chapter 7: Lists

### Even indices
```.py
n = input().split()
for i in range(0,len(n),2):
    print(n[i])
```
![](SnakifyAssets/7.1.jpg)

### Even elements
```.py
n = input().split()
for i in range(len(n)):
    if int(n[i]) % 2 == 0:
        print(n[i])
```
![](SnakifyAssets/7.2.jpg)

### Greater than previous
```.py
a = [int(s) for s in input().split()]
for i in range(1, len(a)):
    if a[i] > a[i-1]:
        print(a[i], end=' ')
```
![](SnakifyAssets/7.3.jpg)

### Neighbors of the same sign
```.py
l = input()
l = l.split()
for i in range(0, len(l)-1):
    if int(l[i]) > 0 and int(l[i+1]) > 0:
        print(l[i], l[i+1])
        break
    elif int(l[i]) < 0 and int(l[i+1]) < 0:
        print(l[i], l[i+1])
        break
```
![](SnakifyAssets/7.4.jpg)

### Greater than neighbours
```.py
l = input().split()
count = 0
for i in range(1, len(l)-1):
    if int(l[i-1]) < int(l[i]) > int(l[i+1]):
        count += 1
print(count)
```
![](SnakifyAssets/7.5.jpg)

### The largest element
```.py
l = input().split()
max = 0
for i in range(len(l)):
    if int(l[i]) > int(l[max]):
        max = i
print(l[max], max)
```
![](SnakifyAssets/7.6.jpg)

### The number of distinct elements
```.py
l = input().split()
count = 1
for i in range(1, len(l)):
    if l[i] != l[i-1]:
        count += 1
print(count)
```
![](SnakifyAssets/7.7.jpg)

### Swap neighbours
```.py
l = input().split()
for i in range(0, len(l)-1, 2):
    l[i], l[i+1] = l[i+1], l[i]
print(' '.join(l))
```
![](SnakifyAssets/7.8.jpg)

### Swap min and max
```.py
l = input().split()
l = [int(i) for i in l]
maxi = max(l)
mini = min(l)
maxi_index = l.index(maxi)
mini_index = l.index(mini)
l[maxi_index] = mini
l[mini_index] = maxi
for i in l:
    print(i, end=' ')
```
![](SnakifyAssets/7.9.jpg)

### The number of pairs in equal
```.py
l = input().split()
count = 0
for i in range(len(l)):
    for j in range(i+1, len(l)):
        if l[i] == l[j]:
            count += 1
print(count)
```
![](SnakifyAssets/7.10.jpg)

### Unique elements
```.py
l = input().split()
for i in l:
    if l.count(i) == 1:
        print(i, end=' ')
```
![](SnakifyAssets/7.11.jpg)

### Queens
```.py
n = 8
x = []
y = []
for i in range(n):
    new_x, new_y = [int(s) for s in input().split()]
    x.append(new_x)
    y.append(new_y)

correct = True
for i in range(n):
    for j in range(i + 1, n):
        if x[i] == x[j] or y[i] == y[j] or abs(x[i] - x[j]) == abs(y[i] - y[j]):
            correct = False

if correct:
    print('NO')
else:
    print('YES')
```
![](SnakifyAssets/7.12.jpg)

### The bowling alley
```.py
s, n = [int(i) for i in input().split()]
pins = ["I" for _ in range(s)]
for i in range(n):
    a, b = [int(i) for i in input().split()]
    for j in range(a-1,b):
        pins[j] = "."
print("".join(pins))
```
![](SnakifyAssets/7.13.jpg)

## Chapter 8: Functions and recursion

### The length of the segment
```.py
def distance(x1, y1, x2, y2):
    from math import sqrt
    return sqrt((x1-x2)**2+(y1-y2)**2)
    
x1 = float(input())
y1 = float(input())
x2 = float(input())
y2 = float(input())
print(distance(x1, y1, x2, y2))
```
![](SnakifyAssets/8.1.jpg)

### Negative Exponent
```.py
def power(a, n):
    return(a**n)
a = float(input())
n = float(input())

print(power(a, n))
```
![](SnakifyAssets/8.2.jpg)

### Uppercase
```.py
def capitalize(word):
    return chr(ord(word[0]) + ord('A') - ord('a')) + word[1:]
    
s = [str(s) for s in input().split()]
for i in range(len(s)):
    s[i] = capitalize(s[i])
print(' '.join([str(i) for i in s]))
```
![](SnakifyAssets/8.3.jpg)

### Exponentiation
```.py
def power(a, n):
    if n == 0:
        return 1
    else:
        return a * power(a, n - 1)

print(power(float(input()), int(input())))
```
![](SnakifyAssets/8.4.jpg)

### Reverse the sequence
```.py
def reverse():
    a = int(input())
    if a != 0:
        reverse()
    print(a)

reverse()
```
![](SnakifyAssets/8.5.jpg)

### Fibonacci numbers
```.py
def fib(n):
    if n == 1 or n == 2:
        return 1
    else:
        return fib(n - 1) + fib(n - 2)

print(fib(int(input())))
```
![](SnakifyAssets/8.6.jpg)


## Chapter 9: Two-dimensional lists(arrays)

### Maximum
```.py
n, m = [int(j) for j in input().split()]
a = [[int(j) for j in input().split()] for i in range(n)]
max_row = 0
max_col = 0
max = a[max_row][max_col]
for i in range(n):
    for j in range(m):
        if max < a[i][j]:
            max = a[i][j]
            max_row = i
            max_col = j
print(max_row, max_col)
```
![](SnakifyAssets/9.1.jpg)

### Snowflakes
```.py
n = int(input())
k = n // 2
a = [['.'] * n for i in range(n)]
for i in range(n):
    a[k][i] = '*'
    a[i][k] = '*'
    a[i][i] = '*'
    a[n-i-1][i] = '*'
for row in a:
    print(' '.join(row))
```
![](SnakifyAssets/9.2.jpg)

### Chess board
```.py
def chessboard(n, m):
    if (n + m) % 2 == 0:
        return '.'
    else:
        return '*'

n, m = [int(j) for j in input().split()]
a = [[chessboard(i, j) for j in range(m)] for i in range(n)]
for row in a:
    print(' '.join(row))
```
![](SnakifyAssets/9.3.jpg)

### The diagonal parallel to the main one
```.py
n = int(input())
a = [[abs(i - j) for j in range(n)] for i in range(n)]
for row in a:
    print(' '.join([str(i) for i in row]))
```
![](SnakifyAssets/9.4.jpg)

### Side diagonal
```.py
n = int(input())
a = [0] * n
a = [[0] * (n - i - 1) + [1] + [2] * i for i in range(n)]
for row in a:
    print(' '.join([str(i) for i in row]))
```
![](SnakifyAssets/9.5.jpg)

### Swap the columns
```.py
def swap_columns(a, i, j):
    for row in a:
        row[i], row[j] = row[j], row[i]
    return a

n, m = [int(k) for k in input().split()]
a = [[int(j) for j in input().split()] for i in range(n)]
i, j = [int(k) for k in input().split()]
for row in swap_columns(a, i, j):
    print(' '.join([str(i) for i in row]))
```
![](SnakifyAssets/9.6.jpg)

### Scale a matrix
```.py
temp = input().split()
n = int(temp[0])
m =int(temp[1])

a = []
for i in range(n):
    a.append([int(j) for j in input().split()])
c = int(input())
for i in range(n):
    for j in range(m):
        a[i][j] *= c
for i in range(n):
    print(*a[i])
```
![](SnakifyAssets/9.7.jpg)

### Multiply two matrices
```.py
temp = input()
m, n, r = temp.split()
m = int(m)
n = int(n)
r = int(r)
A = []
B = []
for i in range(m):
    temp = input()
    A.append(temp.split())
for i in range(n):
    temp = input()
    B.append(temp.split())
for i in range(m):
    for j in range(r):
        temp = 0
        for k in range(n):
            temp += int(A[i][k]) * int(B[k][j])
        print(temp, end=" ")
    print()
```
![](SnakifyAssets/9.8.jpg)

## Chapter 10: Sets

### The number of distinct numbers
```.py
print(len(set(input()))-1)
```
![](SnakifyAssets/10.1.jpg)

### The number of equal numbers
```.py
print(len(set(input().split()) & set(input().split())))
```
![](SnakifyAssets/10.2.jpg)

### The intersection of sets
```.py
print(*sorted(set(input().split()) & set(input().split()), key=int))
```
![](SnakifyAssets/10.3.jpg)

### Has the number been encountered before
```.py
a = input().split()
for i in range(len(a)):
    if a[i] in a[:i]:
        print('YES')
    else:
        print('NO')
```
![](SnakifyAssets/10.4.jpg)

### Cubes
```.py
n, m = [int(j) for j in input().split()]
A = set()
B = set()
for i in range(n):
    A.add(int(input()))
for i in range(m):
    B.add(int(input()))
C = A & B
D = A - B
Е = B - A
print(len(C))
print(*sorted(C), key=int)
print(len(D))
print(*sorted(D), key=int)
print(len(Е))
print(*sorted(Е), key=int)
```
![](SnakifyAssets/10.5.jpg)

### The number of distinct words in some text
```.py
n = int(input())
a = [[j for j in input().split()] for i in range(n)]
print(len(set(sum(a, []))))
```
![](SnakifyAssets/10.6.jpg)

### Guess the number
```.py
n = int(input())
a = [i for i in range(1,n+1)]
s = set(a)
while True:
    guess = input()
    if guess == 'HELP':
        break
    answer = input()
    if answer == 'NO':
        s -= set(guess.split())
    elif answer == 'YES':
        s &= set(guess.split())
print(' '.join([str(i) for i in list(s)]))
```
![](SnakifyAssets/10.7.jpg)

### Polyglots
```.py
students = [{input() for j in range(int(input()))} for i in range(int(input()))]
known_by_everyone, known_by_someone = set.intersection(*students), set.union(*students)
print(len(known_by_everyone), *sorted(known_by_everyone), sep='\n')
print(len(known_by_someone), *sorted(known_by_someone), sep='\n')
```
![](SnakifyAssets/10.8.jpg)

## Chapter 11: Dictionaries
### Number of occurances
```.py
s=input()
def occu(s):
    counter = {}
    string = ''
    for word in s.split():
        counter[word] = counter.get(word, 0) + 1
        string += str(counter[word] - 1) +' '
    return string
print(occu(s))
```
![](SnakifyAssets/11.1.jpg)

### Dictionary of synonyms
```.py
n = int(input())
synonyms = {}
for i in range(n):
    pair = input().split()
    synonyms[pair[0]] = pair[1]
word = input()
for key in synonyms:
    if key == word:
        print(synonyms[key])
    if synonyms[key] == word:
        print(key)
```
![](SnakifyAssets/11.2.jpg)

### Elections in the USA
```.py
n = int(input())
d = {}
for i in range(n):
    key, val = input().split()
    if key in d:
        d[key] += int(val)
    else:
        d[key] = int(val)
for key, val in sorted(d.items()):
    print(key, val)
```
![](SnakifyAssets/11.3.jpg)

### The most frequent word
```.py
counter = {}
for i in range(int(input())):
    line = input().split()
    for word in line:
        counter[word] = counter.get(word, 0) + 1
        
max_count = max(counter.values())
most_frequent = [k for k, v in counter.items() if v == max_count]
print(min(most_frequent))
```
![](SnakifyAssets/11.4.jpg)

### Access rights
```.py
permissions = {}
n = int(input())
for _ in range(n):
     s = input().split()
     permissions[s[0]] = set(s[1:])
for _ in range(int(input())):
     perm, file = input().split()
     if perm == 'read':
         perm = 'R'
     if perm == 'write':
         perm = 'W'
     if perm == 'execute':
         perm = 'X'
     if perm in permissions[file]:
         print('OK')
     else:
         print('Access denied')
```
![](SnakifyAssets/11.5.jpg)

### Countries and cities
```.py
n = int(input())
cities = {}
for _ in range(n):
    line = input().split()
    for city in line[1:]:
        cities[city] = line[0]

for _ in range(int(input())):
    print(cities[input()])
```
![](SnakifyAssets/11.6.jpg)

### Frequency analysis
```.py
counter = {}
for i in range(int(input())):
    line = input().split()
    for word in line:
        counter[word] = counter.get(word, 0) + 1

for i in sorted(counter.items(), key=lambda x:(-x[1],x[0])): 
    print(i[0])
```
![](SnakifyAssets/11.7.jpg)

### English-Latin Dictionary
```.py
n = int(input())
ld = dict()
for i in range(n):
    ew, lw = input().split(" - ")
    lws = lw.split(", ")
    for w in lws:
        if w in ld:
            ld[w].append(ew)
        else:
            ld[w] = [ew]
print(len(ld))
for lw in sorted(ld):
    print(lw, " - ", ", ".join(ld[lw]))
```
![](SnakifyAssets/11.8.jpg)

## The End!
Thanks for reading this till the end!
