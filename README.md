 **Problem: Implement a Queue using Two Stacks**

**Description:**

You are required to implement a class `MyQueue` that simulates a queue using two stacks. The queue should have the following methods:

1. `__init__(self)`: Initializes the queue.
2. `push(self, x: int) -> None`: Pushes the integer `x` to the back of the queue.
3. `pop(self) -> int`: Removes the element from the front of the queue and returns it.
4. `peek(self) -> int`: Returns the element at the front of the queue without removing it.
5. `empty(self) -> bool`: Returns `True` if the queue is empty, `False` otherwise.

**Constraints:**

- You should use only standard stack operations (`push`, `pop`, `peek`, and `empty`).
- All operations should run in average O(1) time.

**Example:**

```python
queue = MyQueue()

queue.push(1)
queue.push(2)
print(queue.peek())   # returns 1
print(queue.pop())    # returns 1
print(queue.empty())  # returns False
```

**Explanation:**

- `queue.push(1)` pushes `1` to the back of the queue.
- `queue.push(2)` pushes `2` to the back of the queue.
- `queue.peek()` returns the element at the front of the queue, which is `1`.
- `queue.pop()` removes and returns the element at the front of the queue, which is `1`.
- `queue.empty()` checks whether the queue is empty, returning `False`.
