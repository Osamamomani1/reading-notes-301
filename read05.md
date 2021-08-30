# Linked Lists

* ## **What is a Linked List?**


        A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image:

![linkedlist](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20200922124319/Singly-Linked-List1.png)
****

* ## **Linked List Types:**

1.  ### Singly Linked List :

        Advantages over arrays 1) Dynamic size 2) Ease of insertion/deletion

        Each node in a list consists of at least two parts: 1) data 2) Pointer (Or Reference) to the next node

![singlylinkedlist](https://miro.medium.com/max/953/1*iiEWrP2IznA6HbmuIdK0lQ.png) 

****
2. ###  Circular Linked List:

        is a linked list where all nodes are connected to form a circle. There is no NULL at the end. A circular linked list can be a singly circular linked list or doubly circular linked list.

![Circular Linked List](https://static.javatpoint.com/corebasic/programs/images/java-program-to-createa-and-display-a-circular-linked-list.png)

### Advantages of Circular Linked Lists:

 1) Any node can be a starting point. We can traverse the whole list by starting from any point. We just need to stop when the first visited node is visited again.

2) Useful for implementation of queue. Unlike this implementation, we don’t need to maintain two pointers for front and rear if we use circular linked list. We can maintain a pointer to the last inserted node and front can always be obtained as next of last.

3) Circular lists are useful in applications to repeatedly go around the list. For example, when multiple applications are running on a PC, it is common for the operating system to put the running applications on a list and then to cycle through them, giving each of them a slice of time to execute, and then making them wait while the CPU is given to another application. It is convenient for the operating system to use a circular list so that when it reaches the end of the list it can cycle around to the front of the list.

4) Circular Doubly Linked Lists are used for implementation of advanced data structures like Fibonacci Heap.
****

3. ### Doubly Linked List

        A Doubly Linked List (DLL) contains an extra pointer, typically called previous pointer, together with next pointer and data which are there in singly linked list.

![Doubly Linked List](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/03/DLL1.png)

### Advantages over singly linked list

 1) A DLL can be traversed in both forward and backward direction.
 
 2) The delete operation in DLL is more efficient if pointer to the node to be deleted is given.

 3) We can quickly insert a new node before a given node. In singly linked list, to delete a node, pointer to the previous node is needed. To get this previous node, sometimes the list is traversed. In DLL, we can get the previous node using previous pointer.

 ****

