# Remove Duplicates from a Sorted Linked List

Given a sorted linked list, remove all duplicates from the linked list. For example, if the given linked list is 11->11->11->21->43->43->60, then the output should be 11->21->43->60.

#### Note:

* The list must be non-decreasing.

## Demo

[https://sauravhathi.github.io/remove-duplicates-from-sorted-list/](https://sauravhathi.github.io/remove-duplicates-from-sorted-list/)

### HomePage
![image](https://user-images.githubusercontent.com/61316762/200314937-ac022612-2d60-4c5f-8421-eaa723b85008.png)

### UI

![image](https://user-images.githubusercontent.com/61316762/200315026-f5fee0d0-67db-446f-a273-43b9c93b806b.png)

### Output 1

![image](https://user-images.githubusercontent.com/61316762/200315149-f3bb177d-9d22-4a38-ab8b-4d03deec5dbe.png)

### Output 2

![image](https://user-images.githubusercontent.com/61316762/200315851-15e7eba4-230e-4ee8-8677-173683858cee.png)

### When list is not sorted

![image](https://user-images.githubusercontent.com/61316762/200315298-83b2d8a3-2109-4445-a9e2-cce0378fe0c7.png)

## Algorithm

1. Traverse the list from the head (or start) node.
2. While traversing, compare each node with its next node.
3. If the data of the next node is the same as the current node then delete the next node. Before we delete a node, we need to store the next pointer of the node.
4. Otherwise, do nothing and move to the next node.

## Time Complexity

The time complexity of the above algorithm is O(n).

## Space Complexity

The space complexity of the above algorithm is O(1).
