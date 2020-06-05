## Stacks

```
letters = []

# Add to stack.
letters.append('a')
letters.append('b')

# Remove from stack.
last_item = letters.pop()

from collections import deque

numbers = deque()

# Use append like before to add elements.
numbers.append(99)
numbers.append(15)

# You can pop like a stack.
last_item = numbers.pop()
```

```
class Stack:
    def __init__(self):
        self.stack = []

    def pop(self):
        if len(self.stack) < 1:
            return None
        return self.stack.pop()

    def push(self, item):
        self.stack.append(item)

peek
isEmpty
    def size(self):
        return len(self.stack)
```

## Queues

```
fruits = []

# Add to queue.
fruits.append('banana')
fruits.append('grapes')

# Remove from queue.
first_item = fruits.pop(0)

from collections import deque

numbers = deque()

# Use append like before to add elements.
numbers.append(99)
numbers.append(15)

# You can pop like a stack.
last_item = numbers.popleft()
```

```
class Queue:
    def __init__(self):
        self.queue = []

    def enqueue(self, item):
        self.queue.append(item)

    def dequeue(self):
        if len(self.queue) < 1:
            return None
        return self.queue.pop(0)

    def size(self):
        return len(self.queue) 
```