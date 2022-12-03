# Day 1
## Topics Covered
1. Struct of Singly Linked List Node.
   ```c++
   struct LLN
   {
     int val;
     LLN* next;
   }; 
   ```
2. Basic Linked List Operations
   1. Accessing and modifying the `val` and `next`.
   2. Allocating the node in heap.
   3. Deleting the node from heap.
   4. Memory Leak and Dangling Pointers.
   5. Why use `--address=sanitizer` in VS Code/gcc/g++.
4. Memory representation of node (Advanced/Optional/Should know for completeness of knowledge/Helps in debugging inside IDE at runtime)
   1. Local variables are always in stack.
   2. Pointers are nothing but address in memory.
   3. Byte level details of what is stored in memory for a linked list of size 3 -- including Little Endian aspects (Requires MuP course knowledge)
5. How `new` and `delete` works (Requires knowledge of MuP course -- Pagetable and signals. People in class had the background in this, so this was covered for completeness)
   1. Role of operating system in `new` and `delete`.
   2. Why `--address=sanitizer` breaks the program on accessing dangling pointer and why accessing dangling pointers without `--address=sanitizer` don't result in runtime error.
6. Linked List Operations
   1. Traversing a linked list and printing the contents (Using Stack and Heap contents along with symbolic representation on a linked list of size 3).
   2. Insertion at the beginning.
   3. Insertion at the end.
   4. Deletion from the beginning.

## Homework
1. Remove Linked List node from end.
2. Find the middle element of linked list using slow/fast pointer approach - Refer [GeeksforGeeks](https://www.geeksforgeeks.org/write-a-c-function-to-print-the-middle-of-the-linked-list/).
