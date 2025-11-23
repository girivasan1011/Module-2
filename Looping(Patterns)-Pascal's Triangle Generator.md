# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
for j in range(a-i-1):
    print(end=" ")
for m in range(i+1):          
         ncr=1
         if(i>0):
            ncr=1
            for k in range(1,m+1):
                 c=(i-k+1)/k
                 ncr=ncr*c
         print(int(ncr), end=" ")
print("")
```

## Sample Output
<img width="1281" height="633" alt="438599024-17390b90-cac6-4e6a-8dc8-01cb1085fa2e" src="https://github.com/user-attachments/assets/5aee70ac-7823-49f3-8d74-c62ee06923e8" />

## Result

Thus, the python program was executed successfully
