# Abigail
UIL Practice Problem

# Abigail
Program Name: Abigail.java Input File: abigail.dat
Abigail has just learned to simplify square root radicals and needs you to write a program for her so she can check her work. The
rules she learned in the lesson were simple:

1. A square root radicand may not contain a perfect root factor.
2. A square root radicand may not be negative.

Her current homework has several expressions in the form A + B * sqrt(C), where A, B, and C can be any integers, positive or
negative, but only A might be zero. The assignment is to simplify the radical in the same form.
The program is to input the initial values of A, B, and C, and then output the simplified values of A, B, and C, any of which
could be zero.

Her teacher has guaranteed that all answers have possible values of A, B, and C, and that when B or C are equal to zero, it means
there is no radical in the final solution.

For example, the data set 5 2 20 represents 5 + 2 * sqrt(20), which can be simplified as such:
5 + 2 * sqrt(4 * 5) = 5 + 2 * 2 * sqrt(5) = 5 + 4 * sqrt(5), resulting in the output values 5, 4 and 5.
For the data set 5 2 -20, the final output is 5 4i 5, with i representing the square root of -1.

Input - Several sets of three integer values, each set on one line. All three integers will be in the range -100...100, but only A
might be zero. Each set of three integers A, B, and C represents the radical expression A + B * sqrt(C).

Output - Simplify each expression according to the rules listed above, and output the final values of A, B, and C. It is possible
for any of the final three values to be zero.
Sample data:
5 2 20</br>
5 2 -20</br>
0 3 9</br>
3 4 -25</br>
0 9 3</br>
Sample Output:
5 4 5</br>
5 4i 5</br>
9 0 0</br>
3 20i 0</br>
0 9 3</br>
