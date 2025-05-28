# Exp. No: 2a  
## ITERATIVE STATEMENTS –Printing 1 to n Odd numbers in reverse order.

###  Aim
To write a program that prints all odd numbers from 1 to n in reverse order (from largest to smallest).

###  Algorithm

1.Start

2.Input an integer n (the upper limit).

3.If n is even, subtract 1 from n to get the largest odd number less than or equal to n.

4.Loop from n down to 1, decrementing by 2:

5.Print the current number.

6.End

### 🧾 Program
#Reg.NO:212222220015

#Name: Hemanth babu M B

```
n=int(input())
for i in range(n,0,-1):
    if(i%2!=0):
        print(i)
```
### OUTPUT

![opmod2](https://github.com/user-attachments/assets/6800b5bc-9a1a-4a0c-a978-cf545c4290b9)

### RESULT 

The program prints all odd numbers from 1 to n in reverse order, starting from the largest odd ≤ n down to 1.








