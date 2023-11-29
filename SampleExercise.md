# Fibonacci Sequence exercise:

## Context

The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones.
The sequence starts with 0 and 1, and goes on to 1,2,3,5,8,13.... etc.

## Task

````
public class Fibonacci {
    // Calculate the N°th Fibonacci number
    public static int calculateFibonacci(<Blank 1> n) {
        // Check condition on n
        <Blank 2> (n <= 1) {
            <Blank 5> n;
        }
        
        int prev = 0;
        int curr = 1;
        int result = 0;
        
        for (int i = 2; i <= n; <Blank 3>) {
            result = prev <Blank 4> curr;
            prev = curr;
            curr = result;
        }
        
        <Blank 5> result;
    }

    public static void main(String[] args) {
        int n = 10; 
        int fibN = calculateFibonacci(n);
        System.out.println("The " + n + "th Fibonacci number is: " + fibN);
    }
}
````

fill in the blanks `<Blank N°>` with the correct code:

- 
- The correct control flow statement
- 

