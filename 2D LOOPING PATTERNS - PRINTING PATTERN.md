# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print Right down Mirror Star Pattern .
---

### ALGORITHM

1.Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3.Run a loop i from 0 to n-1 (total n iterations), each iteration representing a row.
4.For each row i, print 2 * i spaces (multiplied by 2 for better alignment), to shift the stars to the right.
5.Run a loop j from n down to i+1, printing a "* " in each iteration. This ensures that the number of stars decreases with each row.
6.After printing all stars for the current row, move to the next line.
7.Terminate the program.

---

### PROGRAM
```
#Reg.NO 212223020026
#Name SRUTHI.K
#Add Your Code Here
n=int(input())

for i in range(n):
    print(" "*2*i,end="")
    for j in range(n,i,-1):
        print("*",end=" ")
    print("")    
```

### OUTPUT
![image](https://github.com/user-attachments/assets/1bec4e97-6009-4ecd-bedc-a192bd929b9e)


### RESULT
Thus the Python program to print Right down Mirror Star Pattern is executed successfully.
