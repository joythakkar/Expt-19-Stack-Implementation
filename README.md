# Expt-19-Stack-Implementation

# Stack Implementation in C++

## Aim
To implement the **Stack data structure** in C++.

---

## Theory

### What are Stacks?
In C++, a **stack** is a container adapter provided by the Standard Template Library (STL) that implements a stack data structure.  
It operates on the **Last-In, First-Out (LIFO)** principle, meaning the last element added to the stack is the first one to be removed.

---

### Key Characteristics and Operations
- **LIFO Principle** → Elements are added and removed only from the **top** of the stack.  
- **push()** → Adds an element to the top of the stack.  
- **pop()** → Removes the element from the top of the stack.  
- **top()** → Returns a reference to the element at the top of the stack (without removing it).  
- **empty()** → Checks if the stack is empty (`true` if yes, `false` otherwise).  
- **size()** → Returns the number of elements currently in the stack.  

---

### Common Use Cases
Stacks are widely used in programming, including:
- **Function Call Management**
- **Expression Evaluation**
- **Undo/Redo Functionality**
- **Browser History**
- **Syntax Parsing**

---

### Basic Operations
- **Inserting Elements** → Only possible at the top of the stack using `push()`.  
- **Accessing Elements** → Only the top element can be accessed using `top()`.  
- **Deleting Elements** → Only the top element can be removed using `pop()`.  
- **Checking Empty** → `empty()` checks whether the stack has any elements.  
- **Stack Size** → `size()` gives the number of elements currently in the stack.  

---

## Algorithm (Example Flow)
1. Initialize an empty stack.  
2. Push `10` onto the stack.  
3. Push `20` onto the stack.  
4. Push `30` onto the stack.  
   - Display elements → **10 20 30**  
5. Retrieve and display the top element → **30**  
6. Pop the top element (removes `30`).  
   - Display elements → **10 20**  
7. Push `40`, `50`, and `60` onto the stack.  
   - Display elements → **10 20 40 50 60**  

---

## Conclusion
We learnt to implement **basic stack operations** such as push, pop, top, size, and empty in C++.  
Stacks are an essential linear data structure widely used in memory management, parsing, and backtracking problems.
