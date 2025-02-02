# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 02-02-2025                                                                       
### REGISTER NUMBER : 212221040142

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. The program with possible test cases.
5. Stop the program.

### Program:
### i)do..while
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
### ii) while..do
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
### Switch
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
###  if..else
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
### v) for
```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate()
```

### Output:

### do..while
 ![dowhile](https://github.com/user-attachments/assets/da82f173-3a51-4dec-bbd2-89a51dcccec5)

### while..do
 ![whiledo](https://github.com/user-attachments/assets/d34027fd-b37f-4a8b-9df3-97161c39a4f3)

### switch
 ![switch](https://github.com/user-attachments/assets/79a32be6-f440-4bb4-925c-9ad5fcddbda7)

### if..else
 ![ifelse](https://github.com/user-attachments/assets/f07aeaf1-c012-44d0-8a1b-cd6acc4c28a0)

### for
 ![for](https://github.com/user-attachments/assets/69ab7286-c8f6-45e0-8dd5-cdf14a100dd1)
 
### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
