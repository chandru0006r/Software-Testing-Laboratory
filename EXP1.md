# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 24.09.2024                                                                        
### REGISTER NUMBER : 212222040029

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```

### iv.) if else

```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```




### Output:

### i.)do…while: 
![Screenshot (78)](https://github.com/user-attachments/assets/8d26d7c2-b12c-44b7-9a71-8b8a474ff3a7)



### ii.) while…do 

![Screenshot (79)](https://github.com/user-attachments/assets/545571e8-b702-4f12-9540-5ca9151f07ab)


### iii.) switch 
![Screenshot (80)](https://github.com/user-attachments/assets/dd6fa195-9bdc-4fd5-9e5a-aa8250b9118f)


### iv.) if else
![Screenshot (81)](https://github.com/user-attachments/assets/c4899491-1d68-4a5e-864d-0214e10012cb)


### v.) for 

![Screenshot (82)](https://github.com/user-attachments/assets/eb2c99ca-1fb6-4ec7-9086-1a0d9e1bdde3)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
