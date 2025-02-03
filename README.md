# Fibonacci
Fibonacci Series Numbers
Lets get down to the logic 
#####################################################333

public static void printFibonacci(int n) {
    int first = 0, second = 1;

Defines a method printFibonacci(int n), which takes an integer n as input.
Initializes two variables:
first = 0: Represents the first Fibonacci number.
second = 1: Represents the second Fibonacci number.

##########################################################3
for (int i = 0; i < n; i++) {
    System.out.print(first + " ");
    int next = first + second;
    first = second;
    second = next;
}
System.out.println();

Loop Iteration (for loop):
Runs n times, printing each Fibonacci number.
Step-by-step breakdown of the Fibonacci logic:
Print first (which is 0 in the first iteration).
Calculate next as first + second (i.e., sum of previous two numbers).
Update first to second.
Update second to next.
The loop continues until n Fibonacci numbers are printed.
############################################################

Example Walkthrough
Case: User Inputs 7
first = 0, second = 1
Iteration 1 → Print 0, Compute next = 0 + 1 = 1
Iteration 2 → Print 1, Compute next = 1 + 1 = 2
Iteration 3 → Print 1, Compute next = 1 + 2 = 3
Iteration 4 → Print 2, Compute next = 2 + 3 = 5
Iteration 5 → Print 3, Compute next = 3 + 5 = 8
Iteration 6 → Print 5, Compute next = 5 + 8 = 13
Iteration 7 → Print 8
