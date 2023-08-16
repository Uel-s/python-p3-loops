# while loop
```py
num = 0

while num < 6:
    print(num)

    num +=1
   ```

 # For loop

 ```py

 for i in range(10):

    print("looping")

    print(f"i is:{i}")

 ```  

 # for loop

 ```py
 
 for i in range(11):

    print("looping")

    print(f"i is = {i}")

    print (i)

 ```

 ## List Comprehensions

 it is used in;

 1. List comprehensions should only be used for loops where the output is an iterable object such as a list or set.


2. for loops separate steps into different lines, which is how human eyes expect to see instructions. List comprehensions are restricted to a single line and can be difficult for other humans to understand.


`example`

1. I wrote weight in kg and want to convert it to g

```py

weight_in_kg = [0.1,0.2,0.3,0.4,0.5]

weight_in_g = [weight*1000 for weight in weight_in_kg]

print(weight_in_g)


```