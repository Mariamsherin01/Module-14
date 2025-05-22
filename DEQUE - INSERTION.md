# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```
import collections
x=int(input())
y=int(input())
z=int(input())
de=collections.deque([x,y,z])
print("The deque after appending at right is :")
de.append(14)
de.append(15)
print(de)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/2902424a-47fe-4a6a-b7c0-c1704c54e618)

### RESULT
Thus, The Python program to insert elements at REAR END of deque using a collection built-in function is implemented and executed successfully.
