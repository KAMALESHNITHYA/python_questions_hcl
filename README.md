# Python_code

### Question 1:
1. Print all prime numbers between input range (Ex- input 20 50, prints all prime numbers
between 20 and 50).

### Program:
```
a,b=20,50
for i in range(a,b+1):
  c=0
  for j in range(1,50+1):
    if i%j==0:
      c+=1
  if c==2:
    print(i)
```

### Output:
<img width="1572" height="680" alt="image" src="https://github.com/user-attachments/assets/2f929f58-1459-4a47-989f-a3049d9ac4b2" />

### Question 2:
2.Factorial using recursion

### Program:
```
def fact(n):
  if n==0:
    return 1

  return n*fact(n-1)

n=int(input())
print(fact(n))
```

### Output:
<img width="1415" height="487" alt="image" src="https://github.com/user-attachments/assets/fdcbf5d2-fd6b-4a3d-a6e1-4a5c699c939f" />


### Question 3:
3.Square of numbers using lambda

## Program:
```
x=int(input())
for i in range(x+1):
  ans = lambda x : x*x
  print(ans(i))
```

### Output:
<img width="1462" height="537" alt="image" src="https://github.com/user-attachments/assets/6278d338-00b2-4f15-9b67-511ae0b96517" />


### Question 4:
Find the second largest element in a list

### Program:
```
arr = [1,2,3,4,5]
max=float('-inf')
sec_max= float('-inf')

for i in arr:
  if i > max:
    sec_max=max
    max=i
  elif(i!=max and i>sec_max):
    sec_max = i
print(sec_max)
```

### Output:
<img width="1426" height="553" alt="image" src="https://github.com/user-attachments/assets/3532337e-166c-405c-9ab5-53435c49126d" />


### Question 5:
Count frequency of characters in a string

### Program:
```
c="ragav"
d={}
for i in c:
  d[i]=d.get(i,0)+1
print(d)
```

### Output:
<img width="1528" height="546" alt="image" src="https://github.com/user-attachments/assets/8047e4e1-1e27-4302-90e4-cb441be09ba1" />


### Question 6:
Calculate area of a circle using math library.

### Program:
```
import math
r=int(input())
area = math.pi * r * r
print(area)
```

### Output:
<img width="1252" height="550" alt="image" src="https://github.com/user-attachments/assets/7f10db92-dac7-47c0-853e-2c9fd89c2c07" />


### Question 7:
Reverse a string without using built-in reverse

### Program:
```
c='stephen'
rev=""
for i in range(len(c)-1,-1,-1):
  rev+=c[i]
print(rev)
```

### Output:
<img width="1327" height="472" alt="image" src="https://github.com/user-attachments/assets/6c0cd7bd-cb8c-4104-b151-8440f57e3e13" />



### Question 8:
Remove duplicates from a list

### Program:
```
a = [1,2,3,4,5,5]
b = []

for i in a:
    if i not in b:
        b.append(i)

print(b)

```

### Output:
<img width="1365" height="605" alt="image" src="https://github.com/user-attachments/assets/d3c71abf-f035-4158-b21f-aa2b0254c34a" />


### Question 9:
Merge two dictionaries


### Program
```
d1 = {0:1,2:1,3:1}
d2 = {2:3,6:9}
print(list(zip(d1,d2)))
```

### Output:
<img width="1177" height="580" alt="image" src="https://github.com/user-attachments/assets/9e608904-ea89-4b42-8f78-577eb23b029a" />


### Question 10:
Fibonacci series using recursion


### Program:
```
def fib(n):
  if n==0 or n==1:
    return n
  return fib(n-1) + fib(n-2)

n=int(input())

for i in range(n):
  print(fib(i),end=" ")
```



### Output:
<img width="1506" height="637" alt="image" src="https://github.com/user-attachments/assets/aed8d209-a49d-4ed3-aaa7-81a6cc18c485" />







