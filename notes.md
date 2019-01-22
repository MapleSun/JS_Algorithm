# Problem Solving Patterns
## Frequency Counter Pattern
- Use Objects or sets to collect value/frequencies of values
- avoid nested loop or O(n^2) with arrays/strings

## Multiple Pointers
- Creating pointers or values that correspond to an index or position and move towards the begining, end or middle based on a certain condintion
- Very efficient for slving problemds with **minimal space complexity** as well

## Sliding Window
- Creating **window** which can either be an array or number from one position to another
- Depending on a certain condition, the window either increases or closes (and a new window is created)
- Very useful for keeping track of a **subset** of data in an array/string etc.

## Divide and Conquer
- This pattern involves dividing a data set into smaller chunks and then repeating a process with a **subset** of data
- This pattern can termendously **decrease time complexity**

## Recursive
### Important
- Base Case
- return right thing
- stack overflow

### Helper Method Recursion
- result is an array

### Pure Recursion
- concat array before return
- For array, methods like **slice, the spread operator, and concat** that **make copies of arrays** so you do not **mutate** them
- Strings are immutable, use methods like **slice, substr, or substring** to make copies of strings
- Make copies of objects use **Object.assign, or the spread operator**