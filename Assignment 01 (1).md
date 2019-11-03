

```python
print("Twinkle,Twinkle,little star,\n\tHow i wonder what you are!\n\t\tUp above the world so high,\n\t\tLike a diamond in the sky.\nTwinkl twinkle little star,\n\tHow i wonder what yoy are!")
```

    Twinkle,Twinkle,little star,
    	How i wonder what you are!
    		Up above the world so high,
    		Like a diamond in the sky.
    Twinkl twinkle little star,
    	How i wonder what yoy are!
    


```python
import sys
print(sys.version)
```

    3.7.3 (default, Mar 27 2019, 17:13:21) [MSC v.1915 64 bit (AMD64)]
    


```python
from calendar import datetime
now=datetime.datetime.now()
print(now.strftime("%Y-%m-%d %H:%M:%S"))
```

    2019-11-03 15:23:18
    


```python
r=float(input("Input the radius of circle:"))
a=3.142*r**2
print(a)
```

    Input the radius of circle:2
    12.568
    


```python
fname=input("Enter your first name:")
lname=input("Enter your last name:")
print(lname+ " " +fname)
```

    Enter your first name:Wasi
    Enter your last name:Rehman
    Rehman Wasi
    


```python
a=float(input("Enter a number:"))
b=float(input("Enter another number:"))
s=a+b
print(s)
```

    Enter a number:3
    Enter another number:3.6
    6.6
    


```python

```
