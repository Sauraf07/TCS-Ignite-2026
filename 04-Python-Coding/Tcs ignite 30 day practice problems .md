# TCS Ignite — 30-Day Roadmap with Daily Practice Problems

> Solve problems in order within a day — earlier ones warm you up for the harder ones later in the same day. Use Python. Don't check any solution before attempting for at least 10–15 minutes.

---

## Day 1 — Python Syntax Refresh (Loops, Functions, Lists/Dicts/Sets)

1. Print all numbers from 1 to 50 that are divisible by 3 or 5.
2. Write a function that returns the sum of squares of the first N natural numbers.
3. Given a list of numbers, return a new list containing only the even numbers.
4. Write a function `is_palindrome_num(n)` that checks if a number reads the same backward.
5. Count how many vowels are in a given sentence.
6. Given a list of words, return a dictionary mapping each word to its length.
7. Remove duplicate elements from a list while preserving order.
8. Write a function that returns the second largest number in a list.
9. Given two sets of numbers, print their union, intersection, and difference.
10. Write a function `multiply_table(n)` that prints the multiplication table of `n` up to 10.
11. Given a list of dictionaries (each representing a student with name and marks), find the student with the highest marks.
12. Convert a list of tuples into a dictionary.
13. Write a function that flattens a nested list one level deep (e.g., `[[1,2],[3,4]]` → `[1,2,3,4]`).

---

## Day 2 — Time & Space Complexity

1. Write two different functions to find the maximum element in a list — one using a loop (O(n)) and one using `max()` — and explain why both are O(n).
2. Given a list, write a function to check for duplicates using (a) nested loops (O(n²)) and (b) a set (O(n)). Compare mentally why (b) is faster.
3. Write a function that computes the nth Fibonacci number using plain recursion. Identify why it's exponential time.
4. Rewrite the Fibonacci function above using memoization (a dictionary to store computed values) and note the new time complexity.
5. Given a sorted list, write a function to check if a target exists using linear search, then using binary search. Compare complexities.
6. Write a function that counts pairs in a list that sum to a target value — first with O(n²) nested loops, then optimize to O(n) using a set.
7. Given a string, write a function to check if it has all unique characters — first with O(n²), then O(n) using a set.
8. Write a function to reverse a list in place (O(1) extra space) vs. creating a new reversed list (O(n) extra space). Note the space trade-off.
9. Given an array, write a function to find the maximum subarray sum using brute force (O(n²)) — you'll optimize this later once you learn sliding window.
10. Explain (in a comment above each) the time complexity of three of your own Day 1 solutions.

---

## Day 3 — Arrays (Basic)

1. Find the largest and smallest element in an array.
2. Reverse an array in place.
3. Find the sum and average of all elements in an array.
4. Count the number of even and odd elements in an array.
5. Find the second largest element in an array without sorting.
6. Check if an array is sorted in ascending order.
7. Move all zeros in an array to the end while keeping the order of non-zero elements.
8. Find the index of the first occurrence of a target value in an array.
9. Rotate an array to the left by one position.
10. Find the missing number in an array containing numbers from 1 to N with one missing.
11. Merge two sorted arrays into a single sorted array.
12. Find all pairs in an array whose sum equals a given target.

---

## Day 4 — Arrays (Moderate)

1. Find the maximum product of two elements in an array.
2. Rotate an array to the right by K positions (in place, O(1) extra space).
3. Find the majority element in an array (element appearing more than n/2 times).
4. Find the equilibrium index of an array (where left sum equals right sum).
5. Given an array, find the maximum difference between two elements such that the larger comes after the smaller.
6. Rearrange an array so that positive and negative numbers alternate (start with positive).
7. Find all "leaders" in an array (an element is a leader if it's greater than all elements to its right).
8. Given an array of 0s, 1s, and 2s, sort it in a single pass without using built-in sort (Dutch National Flag problem).
9. Find the maximum sum of a subarray of size K (fixed window, without sliding window technique yet — brute force is fine).
10. Given an array, find if there exist three elements whose sum equals a target value.
11. Find the intersection of two arrays (common elements) without duplicates.
12. Find the missing and repeating number in an array of size N containing numbers from 1 to N.

---

## Day 5 — Strings (Basic)

1. Reverse a string without using slicing or built-in reverse.
2. Check if a string is a palindrome.
3. Count the frequency of each character in a string.
4. Check if two strings are anagrams of each other.
5. Convert a string to uppercase and lowercase without using built-in `.upper()`/`.lower()`.
6. Count the number of words in a sentence.
7. Remove all whitespace from a string.
8. Find the first non-repeating character in a string.
9. Check if a string contains only digits.
10. Reverse the order of words in a sentence (e.g., "I am happy" → "happy am I").
11. Find the longest word in a sentence.
12. Check if one string is a rotation of another (e.g., "abcd" and "cdab").

---

## Day 6 — Strings (Moderate)

1. Find the longest palindromic substring in a given string (brute force is fine for now).
2. Compress a string using counts of repeated characters (e.g., "aaabbc" → "a3b2c1").
3. Check if a string can be rearranged to form a palindrome.
4. Find all substrings of a string that are palindromes.
5. Given two strings, find the minimum number of character deletions to make them anagrams.
6. Implement basic string pattern matching — check if a substring exists in a string without using `in`.
7. Given a string, find the length of the longest substring without repeating characters (brute force).
8. Convert a Roman numeral string to an integer.
9. Given a sentence, capitalize the first letter of every word without using `.title()`.
10. Find the longest common prefix among a list of strings.
11. Check if a string follows a given pattern (e.g., pattern "abba", string "dog cat cat dog" → True).
12. Given a string of digits, count how many substrings represent numbers divisible by a given number.

---

## Day 7 — Review Day (Mixed, Light)

1. Redo 3 array problems from Day 3 that you got wrong, from memory (no peeking).
2. Redo 3 string problems from Day 5 that you got wrong, from memory.
3. Given an array, find its sum and reverse it in one function (mini-review combo).
4. Given a string and an array of its characters, check consistency between both approaches (string vs array manipulation).
5. Write the majority element problem (Day 4) again from scratch, faster this time.
6. Write the anagram check (Day 5) again from scratch without checking notes.
7. Pick any 2 Day 4 (Moderate array) problems and try solving them in under 10 minutes each.
8. Pick any 2 Day 6 (Moderate string) problems and try solving them in under 10 minutes each.
9. Write a program combining array + string: given a sentence, return an array of word lengths sorted descending.
10. Self-test: write down (without code) the time complexity of every problem you solved this week.

---

## Day 8 — Hashing Basics

1. Count the frequency of each element in a list using a dictionary.
2. Find the first repeating element in an array using a set.
3. Check if two arrays are equal as sets (contain the same elements, regardless of order).
4. Group anagrams together from a list of strings using a dictionary.
5. Find all elements in an array that occur exactly once.
6. Given two arrays, find elements present in the first but not in the second.
7. Check if a subarray with sum zero exists using a hashset of prefix sums.
8. Find the length of the longest consecutive sequence in an unsorted array (e.g., [100,4,200,1,3,2] → 4, for 1-2-3-4).
9. Count pairs with a given difference K in an array using a set.
10. Given a list of student names, count how many times each name appears using a dictionary.

---

## Day 9 — Hashing Practice

1. Find the first pair of numbers in an array that sum to a target (two-sum, using a dictionary for O(n)).
2. Given an array, find the subarray with the maximum sum that equals a given target sum (using prefix sum + hashmap).
3. Find the longest subarray with a given sum K.
4. Check if an array can be split into two subarrays with equal sum.
5. Given a string, find the first character that repeats.
6. Count distinct elements in every window of size K in an array (using a dictionary).
7. Given two strings, check if one is a permutation of a substring of the other.
8. Find all unique triplets in an array that sum to zero (use hashing to optimize from brute force).
9. Given an array of integers, find the smallest positive integer missing from it.
10. Design a simple frequency-based word counter for a paragraph and print the top 3 most common words.

---

## Day 10 — Stacks

1. Implement a stack from scratch using a Python list (push, pop, peek, is_empty).
2. Check for balanced parentheses in an expression (e.g., "{[()]}" is balanced).
3. Reverse a string using a stack.
4. Evaluate a postfix expression using a stack.
5. Implement a function to check if a sequence of pushes and pops on a stack is valid.
6. Sort a stack using only stack operations (no extra array-based sort).
7. Find the next greater element for each element in an array using a stack.
8. Given a string of digits and operators, remove consecutive duplicate characters using a stack.
9. Convert an infix expression to postfix using a stack.
10. Implement a stack that also supports retrieving the minimum element in O(1).

---

## Day 11 — Queues

1. Implement a queue from scratch using a Python list (enqueue, dequeue, front, is_empty).
2. Implement a queue using two stacks.
3. Implement a circular queue with a fixed size.
4. Given a queue, reverse the first K elements of it.
5. Generate binary numbers from 1 to N using a queue.
6. Implement a basic task scheduler that processes tasks in FIFO order and prints the order of completion.
7. Check if a queue can be sorted using only an auxiliary stack.
8. Implement a sliding window maximum using a deque (introduce yourself to `collections.deque`).
9. Simulate a printer queue — given job priorities, determine the order jobs get printed (FIFO, ignore priority for now).
10. Interleave the first half and second half of a queue (e.g., [1,2,3,4,5,6] → [1,4,2,5,3,6]).

---

## Day 12 — Searching

1. Implement linear search on an unsorted array.
2. Implement binary search on a sorted array (iterative).
3. Implement binary search recursively.
4. Find the first and last occurrence of a target value in a sorted array with duplicates.
5. Find the smallest missing positive number in a sorted array using binary search.
6. Search for a target in a rotated sorted array.
7. Find the peak element in an array (an element greater than both neighbors) using binary search.
8. Find the square root of a number using binary search (without using `**0.5`).
9. Given a sorted array, count how many times a target value appears.
10. Find the smallest element greater than or equal to a target in a sorted array (ceiling search).

---

## Day 13 — Sorting

1. Implement bubble sort from scratch.
2. Implement selection sort from scratch.
3. Implement insertion sort from scratch.
4. Implement merge sort from scratch and note its time complexity.
5. Implement quicksort from scratch and note its worst-case time complexity.
6. Given an array of names and ages, sort by age using a custom key (no need to implement sort from scratch here).
7. Sort an array of 0s, 1s, and 2s using counting sort logic (no comparisons).
8. Given an array, find the number of swaps required to sort it using selection sort logic.
9. Sort an array of strings by length, and for equal lengths, alphabetically.
10. Given two sorted arrays, merge them into one sorted array without using extra space beyond what's needed for the result.

---

## Day 14 — Mini Mock (Mixed, Timed — give yourself 30–40 minutes total)

1. Two-sum problem (array + hashing).
2. Balanced parentheses check (stack).
3. Binary search for a target in a sorted array.
4. Reverse words in a sentence (string).
5. Find the majority element in an array.
6. Merge two sorted arrays.
7. Implement bubble sort and count the number of swaps.
8. Check if a string is a palindrome.
9. Find the first non-repeating character in a string using a dictionary.
10. Find the next greater element for each array element using a stack.

---

## Day 15 — Two Pointers

1. Given a sorted array, find if a pair exists with a given sum.
2. Reverse an array using two pointers (start and end).
3. Remove duplicates from a sorted array in place using two pointers.
4. Given a sorted array, move all zeros to the end while keeping other elements' order.
5. Find the pair with the smallest difference between two sorted arrays.
6. Given an array, partition it around a pivot value (elements less than pivot come first).
7. Find three numbers in a sorted array that sum to a target (3-sum, sorted array approach).
8. Given two sorted arrays, find the median of the combined array using a two-pointer merge.
9. Check if a string is a palindrome using two pointers (start and end index), ignoring non-alphanumeric characters.
10. Given an array of heights, find two lines that together with the x-axis form a container holding the most water.

---

## Day 16 — Sliding Window

1. Find the maximum sum of any subarray of size K.
2. Find the length of the smallest subarray with a sum greater than or equal to a target.
3. Find the longest substring without repeating characters using sliding window (optimize your Day 6 brute force).
4. Find the maximum number of vowels in any substring of length K.
5. Given a string and a pattern, find the smallest window in the string containing all characters of the pattern.
6. Find all anagrams of a pattern string within a larger string.
7. Given an array, find the longest subarray with at most K distinct elements.
8. Find the maximum average value of any contiguous subarray of size K.
9. Given a binary array, find the maximum number of consecutive 1s if you can flip at most K zeros.
10. Find the number of subarrays with exactly K distinct elements.

---

## Day 17 — Recursion (Concept Building)

1. Write a recursive function to print numbers from 1 to N.
2. Write a recursive function to print numbers from N to 1.
3. Write a recursive function to calculate factorial of N.
4. Write a recursive function to calculate the sum of first N natural numbers.
5. Write a recursive function to calculate the nth Fibonacci number.
6. Write a recursive function to check if a string is a palindrome.
7. Write a recursive function to reverse a string.
8. Write a recursive function to compute the power of a number (x^n).
9. Write a recursive function to find the sum of digits of a number.
10. Write a recursive function to count the number of digits in a number.
11. Write a recursive binary search function.
12. Trace (on paper, then verify with code) the call stack for `factorial(5)` step by step.

---

## Day 18 — Recursion (Basic Practice)

1. Recursively find the maximum element in an array.
2. Recursively find the GCD of two numbers.
3. Recursively check if an array is sorted.
4. Recursively reverse an array in place.
5. Recursively find the sum of elements in an array.
6. Recursively count the number of occurrences of a target in an array.
7. Recursively check if a number is a power of 2.
8. Recursively convert a decimal number to binary.
9. Recursively flatten a nested list.
10. Recursively find all divisors of a number.

---

## Day 19 — Recursion (Moderate Practice)

1. Generate all subsets (power set) of a given array using recursion.
2. Generate all permutations of a given string using recursion.
3. Recursively solve the Tower of Hanoi problem and count the number of moves.
4. Given a number N, recursively find all ways to climb N stairs taking 1 or 2 steps at a time.
5. Recursively find all combinations of K numbers from 1 to N.
6. Recursively check if a given sum can be formed using elements of an array (subset sum, boolean check).
7. Recursively merge two sorted arrays.
8. Recursively compute the nth Catalan number.
9. Recursively find the number of ways to express N as a sum of 1, 3, and 4 (order matters).
10. Recursively print all paths from top-left to bottom-right in a grid, moving only right or down.

---

## Day 20 — Recursion (Tricky: Strings/Arrays Combined)

1. Given a string, recursively generate all its subsequences.
2. Given an array of distinct integers, recursively generate all permutations.
3. Recursively find all substrings of a string that are palindromes.
4. Given a string, recursively check if it can be segmented into space-separated words from a given dictionary (word break problem).
5. Recursively generate all valid combinations of balanced parentheses for a given N.
6. Given a phone keypad, recursively generate all possible letter combinations for a given digit string.
7. Recursively find the longest common subsequence between two strings.
8. Recursively count the number of ways to tile a 2xN board using 1x2 tiles.
9. Given an array with duplicates, recursively generate all unique subsets.
10. Recursively check if a target sum can be achieved by choosing +/- signs for each element in an array.

---

## Day 21 — Mini Mock (Mixed, Timed — give yourself 30–40 minutes total)

1. Sliding window: maximum sum subarray of size K.
2. Two pointers: pair with given sum in a sorted array.
3. Recursion: factorial and Fibonacci (write both from scratch, no notes).
4. Recursion: generate all subsets of an array.
5. Recursion: check palindrome.
6. Array: find majority element.
7. String: longest common prefix.
8. Stack: balanced parentheses.
9. Hashing: first repeating element.
10. Searching: binary search on rotated sorted array.

---

## Day 22 — Backtracking (Concept Building)

1. Re-solve your original balls-arrangement problem (G, Y, R counts, no two adjacent same) from scratch, no notes.
2. Print all permutations of the string "ABC" using backtracking.
3. Print all subsets of the array [1,2,3] using backtracking.
4. Given a set of coins and a target, print all combinations that sum to the target (repetition allowed).
5. Solve the N-Queens problem for N=4 (print at least one valid arrangement, then all).
6. Print all ways to place K non-attacking rooks on an N×N chessboard.
7. Given a maze (2D grid with obstacles), print one path from start to end using backtracking.
8. Print all valid combinations of balanced parentheses for N=3 using backtracking (redo from Day 20 with the backtracking framing).
9. Given a string, print all its palindromic partitions using backtracking.
10. Solve a Sudoku-lite version: fill a 4x4 grid with numbers 1-4 such that no row/column repeats (backtracking).

---

## Day 23 — Backtracking Practice 1 (Permutations & Subsets)

1. Generate all permutations of an array with duplicate elements (avoid duplicate permutations in output).
2. Generate all subsets of an array with duplicate elements (avoid duplicate subsets).
3. Given an array and a target, find all unique combinations that sum to the target (each number used once).
4. Given an array and a target, find all combinations that sum to the target (each number can be reused).
5. Print all permutations of a string that don't have two same characters adjacent.
6. Given N and K, print all combinations of K numbers out of 1 to N.
7. Generate all possible letter case permutations of a string (e.g., "a1b" → "a1b", "a1B", "A1b", "A1B").
8. Given a list of words, print all possible concatenation orders (permutations of the list).
9. Print all subsets of an array whose sum is even.
10. Given a 2D grid, print all paths from top-left to bottom-right avoiding obstacle cells.

---

## Day 24 — Backtracking Practice 2 (Constraint-Based Arrangements — Your Core Pattern)

1. Given counts of Green, Yellow, Red balls, print all valid arrangements (not just count) with no two adjacent same.
2. Given counts of 4 different colored balls, extend the above logic and find the total count.
3. Given a string with repeated letters, print all arrangements where no two adjacent letters are the same.
4. Given N people and M languages they can each speak, arrange them in a line so that no two adjacent people share a common language (simplified version — assume 1 language per person).
5. Given a set of tasks with cooldown period K (like Task Scheduler), find the minimum time to complete all tasks with no two same tasks within K of each other.
6. Given G, Y, R ball counts, first check feasibility (is arrangement even possible) before generating arrangements — implement the `max(count) <= ceil(n/2)` rule as a pre-check function.
7. Given a circular arrangement (first and last are also adjacent) of G, Y, R balls, count valid arrangements.
8. Given an array of numbers, arrange them so that no two adjacent numbers have the same parity (odd/even) twice in a row.
9. Given a set of colored beads, print arrangements where no two beads of the same color are within distance 2 of each other (generalize the "no two adjacent" rule to "no two within K").
10. Given a class seating chart requirement (no two students from the same team sit adjacent), model it like the balls problem and solve for a small example (3 teams, sizes given).

---

## Day 25 — Math for Coding

1. Check if a number is prime.
2. Print all prime numbers up to N using the Sieve of Eratosthenes.
3. Find the GCD and LCM of two numbers.
4. Find all factors (divisors) of a number.
5. Check if a number is a perfect square without using `**0.5`.
6. Compute the factorial of a number iteratively and recursively — compare.
7. Find the sum of digits of a number until it becomes a single digit (digital root).
8. Check if a number is an Armstrong number (e.g., 153 = 1³+5³+3³).
9. Compute (a^b) % m efficiently using modular exponentiation.
10. Find the number of trailing zeros in N factorial without computing the full factorial.
11. Given N, find the number of ways to write N as a sum of consecutive positive integers.
12. Convert a number between decimal, binary, octal, and hexadecimal without using built-in conversion functions.

---

## Day 26 — Advanced Mixed Set

1. Find the longest increasing subsequence in an array (brute force or basic DP).
2. Find the maximum subarray sum using Kadane's Algorithm.
3. Given a matrix, rotate it 90 degrees clockwise in place.
4. Find the shortest path in an unweighted grid from start to end using BFS.
5. Given a list of intervals, merge all overlapping intervals.
6. Implement a basic LRU cache using a dictionary (concept-level, not full optimization).
7. Given an array, find the trapping rainwater problem answer (how much water can be trapped between bars).
8. Given a set of jobs with deadlines and profits, find the maximum profit achievable (job sequencing, greedy).
9. Given a string, check if it's a valid number (handles +/-, decimal point, exponent) — parsing/edge-case practice.
10. Given an array, find the minimum number of jumps needed to reach the end (each element = max jump length from there).

---

## Day 27 — Full Mock Test 1 (Timed — simulate real exam conditions, ~60–75 minutes)

1. Two-sum (hashing).
2. Balanced parentheses (stack).
3. Binary search on rotated sorted array.
4. Longest substring without repeating characters (sliding window).
5. Generate all permutations of a string (backtracking).
6. Given G, Y, R ball counts, count valid non-adjacent arrangements (backtracking, your core pattern).
7. Merge overlapping intervals.
8. Find the majority element in an array.
9. Check if a number is prime + print all primes up to N.
10. Reverse words in a sentence.
11. Find the maximum subarray sum (Kadane's).
12. Recursively generate all subsets of an array.

*After finishing: score yourself, note total time taken, and log every mistake with its topic.*

---

## Day 28 — Review Day (Fill Gaps From Mock 1)

1–10. Re-attempt (from scratch, no notes) the specific problems you got wrong or were slow on in Day 27's mock. For each one:
   - Re-read the topic's concept section from earlier days first.
   - Solve it again fully.
   - Then solve one *new* problem of the same topic and difficulty from that day's original list that you haven't tried yet, to confirm the concept has stuck.

*(This day intentionally reuses your mistake log instead of new problems — that's the highest-value use of review time.)*

---

## Day 29 — Full Mock Test 2 (Timed — simulate real exam conditions, ~60–75 minutes)

1. Pair with given sum in a sorted array (two pointers).
2. Group anagrams (hashing).
3. Implement quicksort or merge sort from scratch.
4. Find the next greater element for each array element (stack).
5. Longest common prefix among a list of strings.
6. Generate all valid combinations of balanced parentheses for N=3 (backtracking).
7. Given ball/letter counts, print all valid non-adjacent arrangements + total count (your core pattern, full version).
8. Find the length of the longest subarray with sum K.
9. Check if a string can be segmented using a given word dictionary (recursion).
10. Find the minimum window substring containing all characters of a pattern.
11. Rotate a matrix 90 degrees in place.
12. Compute modular exponentiation (a^b % m).

*After finishing: compare your time and accuracy to Mock 1 — you should be faster and make fewer mistakes.*

---

## Day 30 — Final Light Revision (No New Topics)

1–8. Pick your 2–3 weakest topics across both mocks (e.g., "sliding window" or "backtracking") and solve 3–4 problems from those specific days again, untimed, focusing on clean logic rather than speed.
9–12. Quickly re-read (don't re-solve) your mistake log from Days 14, 21, 27, and 29 — for each mistake, say out loud *why* you got it wrong.
13. Solve exactly one full backtracking problem (your strongest-need area) one last time, fully from scratch, to end prep on a confident note.

*Go into the exam well-rested — Day 30 is about consolidation, not cramming.*