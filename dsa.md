## Array

1. Two Sum
### 2. Best Time to Buy and Sell Stock
```java
class Solution {
    public int maxProfit(int[] prices) {
        int maxProfit = 0, bestBuy = prices[0];

        for(int p : prices) {
            if(p < bestBuy) {
                bestBuy = p;
            }

            maxProfit = Math.max(maxProfit, p - bestBuy);
        }

        return maxProfit;
    }
}
```

### 3. Contains Duplicate
```java
class Solution {
    public boolean containsDuplicate(int[] nums) {
        HashSet<Integer> visitedElements = new HashSet();

        for(int n : nums) {
            if(visitedElements.contains(n)) {
                return true;
            }

            visitedElements.add(n);
        }

        return false;
    }
}
```
### 4. Maximum Subarray
6. Move Zeroes
7. Find All Numbers Disappeared in an Array
8. Single Number
9. Product of Array Except Self
10. Maximum Product Subarray
11. Find Minimum in Rotated Sorted Array
12. Search in Rotated Sorted Array
13. 3Sum
14. Container With Most Water
15. Subarray Sum Equals K
16. Longest Consecutive Sequence
17. Set Matrix Zeroes
18. Spiral Matrix
19. Rotate Array
20. Merge Sorted Array
21. Majority Element

---

## String

1. Valid Palindrome
2. Valid Anagram
3. First Unique Character in a String
4. Reverse String
5. Reverse Words in a String III
6. Longest Common Prefix
7. Implement strStr()
8. Longest Substring Without Repeating Characters
9. Group Anagrams
10. Check if Two String Arrays are Equivalent
11. Longest Palindromic Substring
12. String to Integer (atoi)
13. Minimum Window Substring
14. Decode String
15. Multiply Strings


---

## HashMap / HashSet

1. Two Sum
2. Contains Duplicate
3. Intersection of Two Arrays
4. Happy Number
5. Longest Consecutive Sequence
6. Isomorphic Strings
7. Group Anagrams
8. Top K Frequent Elements
9. Subarray Sum Equals K
10. Word Pattern

---

## Stack

1. Valid Parentheses
2. Min Stack
3. Daily Temperatures
4. Next Greater Element I
5. Evaluate Reverse Polish Notation

---

## Queue

1. Implement Queue using Stacks
2. Number of Recent Calls
3. Design Circular Queue

---

## Recusrsion

1. Fibonacci Number
2. Climbing Stairs
3. Power of Two
4. Generate Parentheses
5. Subsets
