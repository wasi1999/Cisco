
#### Write a program which takes 5 inputs from user for different subject’s marks, total it and generate mark sheet using grades ?


```python
total=500
m1=float(input("Enter marks of subject 1:"))
m2=float(input("Enter marks of subject 2:"))
m3=float(input("Enter marks of subject 3:"))
m4=float(input("Enter marks of subject 4:"))
m5=float(input("Enter marks of subject 5:"))
sum=m1+m2+m3+m4+m5
per=(sum/500)*100
if per>=90:
    print("Grade is A+")
elif per<90 and per>=80:
    print("Grade is A")
elif per<80 and per>70:
    print("Grade is B")
elif per<70 and per>=60:
    print("Grade is C")
elif per<60 and per>=70:
    print("Grade is D")
else:
    print("You are fail")
```

    Enter marks of subject 1:66
    Enter marks of subject 2:77
    Enter marks of subject 3:88
    Enter marks of subject 4:99
    Enter marks of subject 5:67
    Marksheet
    Grade is B
    

 #### 2. Write a program which take input from user and identify that the given number is even or odd? 


```python
n=int(input("Enter a number:"))
if n%2==0:
    print(n," is even number")
else:
    print(n," is odd number")
```

    Enter a number:199
    199  is odd number
    

#### 3. Write a program which print the length of the list? 


```python
a=[4,6,3,7,9,2,5,66,4]
len(a)

```




    9



#### 4. Write a Python program to sum all the numeric items in a list? 


```python
total = 0
list1 = [11, 5, 17, 18, 23]  
for ele in range(0, len(list1)): 
    total = total + list1[ele] 
print("Sum of all elements in given list: ", (total) ) 

```

    Sum of all elements in given list:  74
    

#### 5. Write a Python program to get the largest number from a numeric list. 


```python
a=[4,6,3,7,9,2,5,66,4]
max(a)
```




    66



#### 6. Take a list, say for example this one: a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89] and write a program that prints out all the elements of the list that are less than 5. 


```python
list=eval(input("Enter a list:"))
for i in list:
    if i<5:
        print(i,end="")
```

    Enter a list:1,2,3,4,5,6,7
    1234


```python

```
