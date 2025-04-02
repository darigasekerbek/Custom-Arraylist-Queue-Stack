# MyArrayListQueue and MyArrayListStack - Custom Generic Data Structures

## Overview
This project features the implementation of two custom generic data structures using Java's `ArrayList`: **MyArrayListQueue** (Queue) and **MyArrayListStack** (Stack). Both classes provide fundamental operations to manage and manipulate elements efficiently while ensuring flexibility through generics.

### Key Features:
- **Generic Implementation**: Both classes are designed with generics for type safety and flexibility.
- **Queue Implementation**: Implements FIFO (First-In, First-Out) logic for the `MyArrayListQueue` class.
- **Stack Implementation**: Implements LIFO (Last-In, First-Out) logic for the `MyArrayListStack` class.
- **Full CRUD Operations**: Add, remove, peek, and check the size for both data structures.
- **Exception Handling**: Proper handling for edge cases, including throwing exceptions when performing operations on empty structures.

---

## MyArrayListQueue - Queue Implementation

The `MyArrayListQueue` class implements a queue using an `ArrayList`. It supports standard queue operations like enqueue, dequeue, peek, and checking if the queue is empty.

### Methods:

- **`enqueue(T item)`**  
  Adds an element to the end of the queue.
  
- **`T dequeue()`**  
  Removes and returns the element at the front of the queue. Throws `NoSuchElementException` if the queue is empty.

- **`T peek()`**  
  Returns the element at the front of the queue without removing it. Throws `NoSuchElementException` if the queue is empty.

- **`boolean isEmpty()`**  
  Returns `true` if the queue is empty, otherwise returns `false`.

- **`int size()`**  
  Returns the number of elements in the queue.

---

## MyArrayListStack - Stack Implementation

The `MyArrayListStack` class implements a stack using an `ArrayList`. It supports typical stack operations like push, pop, peek, and checking if the stack is empty.

### Methods:

- **`push(T item)`**  
  Adds an element to the top of the stack.

- **`T pop()`**  
  Removes and returns the element at the top of the stack. Throws `EmptyStackException` if the stack is empty.

- **`T peek()`**  
  Returns the element at the top of the stack without removing it. Throws `EmptyStackException` if the stack is empty.

- **`boolean isEmpty()`**  
  Returns `true` if the stack is empty, otherwise returns `false`.

- **`int size()`**  
  Returns the number of elements in the stack.

---

## Example Usage

### Using `MyArrayListQueue`:

```java
MyArrayListQueue<Integer> queue = new MyArrayListQueue<>();
queue.enqueue(10);
queue.enqueue(20);
queue.enqueue(30);
System.out.println(queue.peek());  // Output: 10
System.out.println(queue.dequeue());  // Output: 10
System.out.println(queue.size());  // Output: 2
```

### Using `MyArrayListStack`:

```java
MyArrayListStack<String> stack = new MyArrayListStack<>();
stack.push("Alice");
stack.push("Bob");
stack.push("Charlie");
System.out.println(stack.peek());  // Output: Charlie
System.out.println(stack.pop());  // Output: Charlie
System.out.println(stack.size());  // Output: 2
```
## Conclusion
This project demonstrates custom generic implementations of a queue and a stack using Java's ArrayList. Both data structures are designed to efficiently manage elements, and the project emphasizes flexibility, exception handling, and scalability.

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Contact
**Author: Dariga Sekerbek**

**GitHub: @darigasekerbek**

**Email: darigasekerbek2@gmail.com**
