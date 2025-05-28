# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To Write a program in python to compute whether the given number is a palindrome

---

### ALGORITHM
 Reg no: 212223090002
 Name: Deepapritha A
1. Begin the program.  
2. Read the number `num` from the user using `input()`.  
3. Copy the value of num into another variable called temp.
4.Set a variable rev (reverse) to 0 and Repeat the following steps while temp is greater than 0
5. Get the last digit of temp using temp % 10.
    Multiply rev by 10 and add the last digit to it.
    Remove the last digit from temp using integer division (temp = temp // 10).  
     After the loop ends, compare rev with num.    
6.If rev is equal to num, print "The number is a palindrome".
7.Otherwise, print "The number is not a palindrome".
8. Terminate the program.

---

### PROGRAM
NAME : HEMANTH BABU M B
REG.NO: 212222220015
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```
### OUTPUT
![image](https://github.com/user-attachments/assets/c793d55f-05dc-4a83-8dce-a79d0dee3e8d)


### RESULT
Thus the python program for computing whether the given number is a palindrome is executed successfully.
