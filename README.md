# Number-Wall-Code
This code should be run in Python. 
Assume m is a prime number.
The function PrintNW(seq,m) creates a PNG of the number wall of the finite sequence Seq over F_m. Best for viewing large number walls.
The function PrintNwSpaced(seq,m) does the same, but adds spaces between the entries of the number wall. Best for viewing smaller number walls.
The colours used in both these images can be edited in the code. 
The function defn(size,m) counts how many sequences over F_m have do not have any windows of size larger than 'size'. 
This works recusrively. It prints the number of sequences of length n with no windows larger than 'size'. 
If there are infinitely many sequences whose number wall has no windows larger than 'size', the function will not terminate.
For example, defn(1,2) counts how many sequences over F_2 have no windows of size larger than 1. It shows that every sequence of length 14 has a window of size 2. 
