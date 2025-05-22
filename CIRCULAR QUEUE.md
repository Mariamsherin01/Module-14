# Exp No: 36  
## Circular Queue 
---

### AIM  
To write a Python program with a function to insert float values into a Circular Queue.

---

### ALGORITHM

1. Start  
2. Check if the Circular Queue is full  
   - If `size == max_size`, print `"Queue is full"` and exit the function  
3. If the queue is not full:  
   - Read the element to be inserted  
   - Convert it to float  
   - Insert the element at the `tail` position  
   - Update tail using: `tail = (tail + 1) % max_size` (circular increment)  
   - Increment `size` by 1  
4. End

---

### PROGRAM

```
class Queue:
    def __init__(self,size):
        self.items=[0]*size
        self.maxsize=size
        self.front,self.size,self.rear=0,0,0
    def is_full(self):
        if self.size==self.maxsize:
            return True
        return False
    def is_empty(self):
        if self.size==0:
            return True
        return False
    def enqueue(self,item):
        if self.is_full():
            print("Queue is full")
            return 
        self.items[self.rear]=item
        self.rear=(self.rear+1)%self.maxsize
        self.size+=1
size=int(input())
n1=float(input())
n2=float(input())
n3=float(input())
obj=Queue(size)
obj.enqueue(n1)
obj.enqueue(n2)
obj.enqueue(n3)
print(obj.items)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/4d911612-f8cd-4cf3-af70-3ae81dac4e90)


### RESULT
Thus, The Python program with a function to insert float values into a Circular Queue is implemented and executed successfully.
