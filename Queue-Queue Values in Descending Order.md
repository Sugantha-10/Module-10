# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 
class Generate:<br>
    def __init__(self, first,d,last):<br>
        self.first = first<br>
        self.d = d<br>
        self.last=<br>
    def Ap_generate(self):<br>
        L=[i for i in range(self.first,self.last+1,self.d)]<br>
        return L<br>
Series = Generate(200,2,301)<br>
print(Series.Ap_generate())

## OUTPUT:
<img width="1225" height="174" alt="image" src="https://github.com/user-attachments/assets/6f9d1c4e-b39d-4a18-a252-2770319ae0b8" />

## RESULT:
Thus the output is verified
