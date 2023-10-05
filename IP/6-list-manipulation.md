# 04/10/23 

```py
a = 5 
b = 6
c = a + b 
print(c)  # 11
```

Similarly, 

```py
a = 5 
a = 3 
b = 2 
c = a+b 
print(c)  #  5 
```

But for this case, the replaced variable gets deleted. This is the problem of python

- Storage also becomes difficult with huge number of variables. 

List solves that problem 

```py
     0  1  2  3  4  5
E = [50,60,70,80,90,100]
M = [50,60,70,80,90,100]
```

The numbers above are called index value or address.  
They always start from zero. 

```py
print(E[0])  # 50 
print(E[5])  # 100 
```
> The above shows index numbers are used to locate values within a list. 

- **Index value**:
    1. Positive Index Value 
    2. Negative Index Value

- Negative Index value ends with -1 

```python
B = [50,60,70,80,90]
     -5 -4 -3 -2 -1 
```

> It works like a number line. 

## Types of Lists 

```py
a = [1,2,,3,4,5] # Integer list  
b = [1.6,2.3,3.9,4.4,5.6] # Floating-point list  
c = ['W','O','R','L','D'] # Character list  
d = ['so','sehr','schon']  # Word List  
e = [1, 3.5, -2, 'Sekai','L'] # Mixed list   
```

- For calculations, only pure list of one type is applicable. 

## Creating an Empty List 

Q = List[]

- Sequence is also a kind of list 

`a = (1,2,3,4,5) # This is a sequence`

- List follows index values but sequences do not. 

### Converting Sequence to a list 

```py 
a = (1,2,3,4,5)
b = List[a]

print(b) # [1,2,3,4,5]
print(a) # (1,2,,3,4,5)

```

- Sequence can be converted into list but not vice versa. 

# 05/10/2023

## List VS String 

- List: mutable 
- String: non-mutable 

Prog1

Write a program to print the positive and negative indexes of each element of a sequence which is given below along with the elements. (['s','c','h','o','o','l'])

```py
a = ['s','c','h','o','o','l']
L = len(a)
n = 0 

for n in range(L):
    print('At indexes', n, "and", (n-L), 'element is:', (a[n]))

```
> The output will be the following   
> At indexes 0 and -6 element is: s   
> At indexes 1 and -5 element is: c  
> At indexes 2 and -4 element is: h  
> At indexes 3 and -3 element is: o  
> At indexes 4 and -2 element is: o  
> At indexes 5 and -1 element is: l  

- ONLY ADDITION OF ELEMENTS IS ALLOWED IN LISTS 
- AND TWO LISTS CANNOT BE MULTIPLIED


```python

# Program to combine lists

A = [1,2,3,4]
B = [1,2,3]

C = A+B 

print(C) # [1,2,3,4,1,2,3]

```

```python
# Program to multiply the element of list 

B = [1,2,3]
B = B*3 

print(B) # [1,2,3,1,2,3,1,2,3]
```

```python
# Program to check for equal content in list 

A = [1,2,3,4]
B = [1,2,3]

if A == B: 
    print('Equal')
else: 
    print('Not equal')
```

- "Greater than and less than functions can also be used."

## Making new list from existing list 

```python
A = [1,2,3,4,5,6,7]
B = A[3:6]

print(B) # [4,5,6]

# For reverse 

B = A[::-1]
print(B) # [7,6,5,4,3,2,1]

# Skipping values 

B = A[0:5:2]
print(B) # [1,3,5]
```