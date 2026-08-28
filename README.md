# LeetCode 40 - Combination Sum II

## Problem

Given an array of integers and a target value, find all unique combinations where the numbers add up to the target.

Each number can be used only once.

## Example

Input:

```text id="x8w0k3"
candidates = [10,1,2,7,6,1,5]
target = 8
```

Output:

```text id="x1c9mv"
[[1,1,6],[1,2,5],[1,7],[2,6]]
```

## Approach

I first sort the array so that duplicate combinations can be avoided.

Then I use backtracking to try different numbers. Once a number is used, I move to the next position because each number can be used only once.

## Complexity

* Time Complexity: `O(2^n)`
* Space Complexity: `O(n)`

## Topics

* Array
* Backtracking
* Sorting

## Language

Python

## Author

T.Nandhini
