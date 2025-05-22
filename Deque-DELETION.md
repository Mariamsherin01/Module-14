# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
import collections
x=input()
y=input()
z=input()
de=collections.deque([x,y,z])
de.pop()
print("The deque after deleting at right is :")
print(de)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/5a14feed-9697-4a3c-a637-776e4ec35e02)


### RESULT
Thus, The Python program to delete elements at FRONT END of deque using a collection built-in function was implemented and executed successfully.
