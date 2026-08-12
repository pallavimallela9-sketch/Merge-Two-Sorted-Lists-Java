# Merge Two Sorted Lists - Java

## Problem Statement

Given two sorted linked lists, merge them into one sorted linked list.

## Example

Input:

List 1: 1 -> 2 -> 4

List 2: 1 -> 3 -> 4

Output:

1 -> 1 -> 2 -> 3 -> 4 -> 4

## Approach

The solution compares the first nodes of both lists.

- Take the smaller value.
- Move that list forward.
- Continue until one list becomes empty.
- Add the remaining nodes to the result.

## Complexity

- Time Complexity: O(n + m)
- Space Complexity: O(1)

## Language

Java

## Data Structure

Linked List

## Author

M. Pallavi
