# Tree

* Using binary tree  needs recursion to be implemented , and the most common case to use and understand recursion is factorial or summation,SUM(n)= n+SUM(n-1) till we reach 0 witch is the base case

same with trees we start with the root till we reach the base case (leaves) 

```
n=20

SUM(n) {
    if (n==0) return 0 
    return n + SUM(n-1)
}

Output-->20+19+18+...+1+0
```

* without knowing teh high of the tree or the number of nodes we could itrate on each node of the tree using recursion same way 

***

### Traversals

![tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/tree-example.png)

An important aspect of trees is how to traverse them. Traversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:

1. **Depth First**

    * Pre-order: `root >> left >> right`
    * In-order: `left >> root >> right`
    * Post-order: `left >> right >> root`



```
ALGORITHM preOrder(root)

    OUTPUT <-- root.value

    if root.left is not Null
        preOrder(root.left)

    if root.right is not NULL
        preOrder(root.right)
```

```
ALGORITHM inOrder(root)

    if root.left is not NULL
        inOrder(root.left)

    OUTPUT <-- root.value

    if root.right is not NULL
        inOrder(root.right)
```

```
ALGORITHM postOrder(root)

    if root.left is not NULL
        postOrder(root.left)

    if root.right is not NULL
        postOrder(root.right)

    OUTPUT <-- root.value
```

2.  **Breadth First**

```
ALGORITHM breadthFirst(root)

  Queue breadth <-- new Queue()
  breadth.enqueue(root)

  while breadth.peek()
    node front = breadth.dequeue()
    OUTPUT <-- front.value

    if front.left is not NULL
      breadth.enqueue(front.left)

    if front.right is not NULL
      breadth.enqueue(front.right)
```

***

### Binary Tree Vs K-ary Trees

1. **Binary Tree**

In previos examples, we’ve been using a Binary Tree. Trees can have any number of children per node, but Binary Trees restrict the number of children to two (hence our left and right children).

2. **K-ary Tree**

If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use K to refer to the maximum number of children that each Node is able to have.

***