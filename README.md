# DSAassignment2

## Question 1

Here is a link to the solution to this question - https://leetcode.com/problems/invert-binary-tree/solutions/4613514/question-1/

### Approach
We traverse the given tree and upon encountering a parent node, we swap its left and right subtree.

### Complexity
- #### Time Complexity - O(n)
- #### Space Complexity - O(h)
  where h is the height of the tree (because of the stack space)

![Screenshot 2024-01-23 162414](https://github.com/RaashiK16/DSAassignment2/assets/126188705/2c6b9bd7-e18e-4214-b657-ae8820b9f057)



## Question 2

Here is a link to the solution to this question - https://leetcode.com/problems/lru-cache/solutions/4630340/question-2/

### Approach
We need to maintain a fixed-size cache of key-value pairs using a doubly linked list and an unordered map. When we access or add a key-value pair, it moves the corresponding node to the front of the linked list, making it the most recently used item. This way, the least recently used item is always at the end of the list. When the cache is full and a new item is added, it removes the item at the end of the list (least recently used) to make space for the new item, ensuring the LRU property is maintained.

### Complexity
- #### Time Complexity - O(1)
- #### Space Complexity - O(n)

![Screenshot 2024-01-26 200038](https://github.com/RaashiK16/DSAassignment2/assets/126188705/21855e48-7a73-48f4-b60e-11c92a562084)


## Question 3

Here is a link to the solution to this question - https://leetcode.com/problems/validate-binary-search-tree/solutions/4613811/question-3/

### Approach
For this question, we will recursively check if the left and right subtrees are a BST within the given range of values. That is, we need to ensure that each node follows the property where the values in the left subtree are less than the node's value, and the values in the right subtree are greater than the node's value.

### Complexity
- #### Time Complexity - O(n)
- #### Space Complexity - O(h)
  where h is the height of the tree (because of the stack space)

![Screenshot 2024-01-23 173246](https://github.com/RaashiK16/DSAassignment2/assets/126188705/1effa8cd-5c39-4bca-ac26-790f05255777)


## Question 4

Here is a link to the solution to this question - https://leetcode.com/problems/jump-game-vii/solutions/4630321/question-4/

### Approach
The problem can be solved by sliding window approach. That is, if we can find an index between minJump and maxJump with which we can reach the last index, we return true, otheriwse false.

### Complexity
- #### Time Complexity - O(n)
- #### Space Complexity - O(n)

![Screenshot 2024-01-26 212141](https://github.com/RaashiK16/DSAassignment2/assets/126188705/793fd25e-bee4-4bc6-b8cb-abf3ebbe6e91)








