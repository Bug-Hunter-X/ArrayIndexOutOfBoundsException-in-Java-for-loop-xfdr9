# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The bug arises from an off-by-one error in a `for` loop that iterates one element past the valid index range of an array.

## Bug Description
The provided Java code attempts to access an array element beyond its bounds, causing an `ArrayIndexOutOfBoundsException`. The loop condition `i <= arr.length` should be corrected to `i < arr.length` to prevent this issue.

## Solution
The solution involves adjusting the loop condition to iterate correctly within the array bounds, thus avoiding the index out-of-bounds error. 

## How to Reproduce
1. Clone the repository.
2. Compile the code using a Java compiler (javac).
3. Run the compiled code (java Main).
4. Observe the `ArrayIndexOutOfBoundsException` that occurs.

## How to Fix
1. Replace the incorrect loop condition `i <= arr.length` in the `Main.java` file with `i < arr.length`.
2. Recompile and run the corrected code to verify the fix.