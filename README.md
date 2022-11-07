# Remove Duplicates from a Sorted Linked List

Given a sorted linked list, remove all duplicates from the linked list. For example, if the given linked list is 11->11->11->21->43->43->60, then the output should be 11->21->43->60.

#### Note:

* The list must be non-decreasing.

## Demo

[https://sauravhathi.github.io/remove-duplicates-from-a-sorted-linked-list/](https://sauravhathi.github.io/remove-duplicates-from-a-sorted-linked-list/)



## Algorithm

1. Traverse the list from the head (or start) node.
2. While traversing, compare each node with its next node.
3. If the data of the next node is the same as the current node then delete the next node. Before we delete a node, we need to store the next pointer of the node.
4. Otherwise, do nothing and move to the next node.

## Time Complexity

The time complexity of the above algorithm is O(n).

## Space Complexity

The space complexity of the above algorithm is O(1).