Big O is also known as "upper boundary". Means, the worst case of algorithms.

> **O(1) __Constant time**
     *Real life example:* Bookmarks = You can directly switch to your desired page.
    * math operations
    * accessing an array via the index
    * accessing a hash via the key
    * pushing and popping on a stack
    * insertion and removal from a queue
    * returning a value from a function

> **O(n) __Linear time**
    O(n) means that the run time increases at the same pace as the input.
    *Real life example:* Reading book = If you read a page in 1 min. then you'll read 30 pages in 30 mins.

    You'll see it while traversing the array: for loop etc.

> **O(n^2) __Quadratic time**
    worst case algorithm: mostly used in sorting.

    * Bubble sort
    * Insertion sort
    * Selection sort

> **O(log n) __Logarithmic time**
    O(log n) means that the running time grows in proportion to the logarithm of the input size, meaning that the run time barely increases as you exponentially increase the input.

    *Real life example:* Finding the word in dictionary by halving it.

    * Binary search operation

> **O(n log n) __Linearithmic(linear+logarithmic)**
    Sorting algorithms that utilize a divide and conquer strategy are linearithmic. See the examples below: -

    * merge sort
    * timsort
    * heapsort

Source: [Big-O Notation: A simple explanation with examples](https://www.linkedin.com/pulse/big-o-notation-simple-explanation-examples-pamela-lovett/)    