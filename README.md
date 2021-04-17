# Grokking Algorithms

This is the code in my book [Grokking Algorithms](https://www.manning.com/bhargava).

Check out [Python Tutor](http://pythontutor.com/), a great website that guides you through Python code line by line.

## Errata

[Here's the errata page](http://adit.io/errata.html).

## Images

This repository contains every image in Grokking Algorithms in high resolution. These images are available for non-commercial use. If you use an image, please add "copyright Manning Publications, drawn by adit.io". You are welcome to use these images in any non-commercial materials (i.e. teaching materials, presentations, etc.)

## Contributing

- The examples in this book are written in Python, but I'd like examples in Ruby, JavaScript, C, and other languages too. Please add examples in other languages!
- Pull request are the quickest way to contribute to this repository but unfortunately I am not as responsive to them as I'd like to be. I'll get to them but it might take a while!

## Notes

### Chapter 1. Intro to Algorithms
- Logs are the flip of exponentials (log 8 == 3 because 2 ^ 3 == 8)
- Big O notation lets you compare the number of operations. It tells you how fast the algorithm grows.
- Algorithm speed isn't measure in seconds, but in growth of the number of operations
- We talk about how quickly the run time of an algorithm increases as the size of the input increase
- Run time of algorithms is expressed in Big O notation
- O(log n) is faster than O(n), and it gets a lot faster once the list of items you're searching grows


### Chapter 2. Selection Sort
- With an array, all your elements are stored right next to each other
- With a list, elements are strewn all over, and one element stores the address of the next one
- Arrays allow fast reads
- Linked lists allow fast inserts and deletes
- All elements in an array should be the same type (all ints, all strs, and so on)

### Chapter 3. Recursion
- Recursion is when a function calls itself
- Every recursive function has two cases: the base case and the recursive case
- A stack has two operations: push and pop
- All function calls go onto the call stack
- The call stack can get very large, which takes up a lot of memory

### Chapter 4. Quicksort
- Divide and Conquer (D&C) works by breaking a problem into smaller and smaller pieces. If you're using D&X on a list, the base case is probably an empty array or an array with one element
- To solve a problem using D&C, there are two steps:
  1. Figure out the base case. This should be the simplest possible case.
  2. Divide or decrease your problem until it becomes the base case.
- D&C isn't a simple algorithm that you can apply to a problem. It's a way to think about a problem.
- If you're implementing quicksort, choose a random element as the pivot. The average runtime of quicksort is O(n log n)
- The constant in Big O notation can matter sometimes. This is why quicksort is faster than merge sort
- The constant almost never matters for simple search versus binary search, because O(log n) is so much faster than O(n) when your list gets big.

### Chapter 5. Hash Tables
- Hash tables have really fast search, insert, and delete.
- Hash tables are good for modeling relationships from one item to another item.
- Hash tables are used for caching data (for example, with a web server).
- Hash tables are great for catching duplicates.


