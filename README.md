## Python Program to Insert Elements at Rear End of Deque Using collections Module

## Aim:
To use Python’s collections.deque and insert characters 'h', 'o', and 'n' at the rear end of the deque.

## Procedure:

1.Import the deque class from the collections module.

2.Initialize an empty deque.

3.Use the append() method to insert each element ('h', 'o', 'n') at the rear.

4.Display the final contents of the deque.

## Program:

```python

from collections import deque

# Initialize empty deque
dq = deque()

# Insert elements at rear
dq.append('h')
dq.append('o')
dq.append('n')

# Display deque contents
print("Deque after inserting at rear:", list(dq))
```
## Output:
![image](https://github.com/user-attachments/assets/9d18c04a-06f6-4892-8c48-2ed782810eff)


## Result:
The deque contains the elements inserted at the rear end:
Deque after inserting at rear: ['h', 'o', 'n']
