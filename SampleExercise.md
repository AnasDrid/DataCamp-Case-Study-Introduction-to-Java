# Chapter 2 Lesson 4 Exercise:

## Fibonacci Sequence exercise: 


## Context

The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones.


The sequence starts with 0 and 1, and goes on to 1,2,3,5,8,13.... etc.

### Example:

We want to calculate the 5th Fibonacci number:

By definition:

1st Fibonacci number: `N°0` = 0 

2nd Fibonacci number: `N°1` = 1

And since we know that `N°x` = `N°x-1` + `N°x-2`

we can calculate the 5th number `N°5`:

`N°2` = `N°1` + `N°0` = 1 + 0 = 1

`N°3` = `N°2` + `N°1` = 1 + 1 = 2

`N°4` = `N°3` + `N°2` = 2 + 1 = 3

`N°5` = `N°4` + `N°3` = 3 + 2 = 5



## Task

The following code calculates the `Nth` Fibonacci number:

### Code

````
public class Fibonacci {
    // Calculate the N°th Fibonacci number
    public static <????> calculateFibonacci(<????> n) {
        // verify the value of n
        ---------
        
        <insert code here>
        
        ---------
        
        int prev = 0;
        int curr = 1;
        int result = 0;
        
        // Calculate the Nth Fibonacci number  
        ---------
        
        <insert code here>
        
        ---------
        
        <????> result;
    }

    public static void main(String[] args) {
        // Calculate and print the 12th Fibonacci number
        ---------
        
        <insert code here>
        
        ---------
    }
}
````

### Instructions

- Fill in the blanks `<????>` with the correct reserved word: `while`, `override`, `char`, `int`, `return`, `void`. N.B: the same code can be used multiple times.
- Check for special cases.
- write the code that calculates the `Nth` number of the Fibonacci sequence.
- Calculate and print the 12th Fibonacci number.

