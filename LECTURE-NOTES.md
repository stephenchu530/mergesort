# Lecture Notes: Merge Sort

This sort is one of the basic sorts used in computer science. We should care because it is a stepping stone to greater and bigger things.

Insertion Sort has the following performance profile:
* Time Complexity: `O(nlg(n))`
* Space Complexity: `O(1)`

## Learning Objectives:
The student will learn the following:
* Merge sort algorithm
* Java implementation
* Unittests for the code
* Time and space complexity

## Lecture Flow:
Main Point:
 * Insertion Sort behaves like arranging playing cards in your hand.
 * Start from the left, and work your way toward the right.
 * Start with the second card, lift it and insert it back into your hand relative the the card to the left.
 * Go to the next card and repeat until the end.

## Diagram
![Visual Diagrom](mergesort.jpg)

## Algorithm

## Pseudocode
Gotten from Code Fellows:
```
    InsertionSort(int[] arr)
  
    FOR i = 1 to arr.length
    
      int j <-- i - 1
      int temp <-- arr[i]
      
      WHILE j >= 0 AND temp < arr[j]
        arr[j + 1] <-- arr[j]
        j <-- j - 1
        
      arr[j + 1] <-- temp
```

## Readings and References
Watch
* [Insertion Sort in 2 Minutes](https://www.youtube.com/watch?v=JU767SDMDvA)

Read
* [Geeks for Geeks](https://www.geeksforgeeks.org/insertion-sort/)
* [Tutorial Point](https://www.tutorialspoint.com/data_structures_algorithms/insertion_sort_algorithm.htm)

Bookmark
* [Wiki Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort)