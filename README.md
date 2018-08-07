# B+ tree
Implementation of B+ tree in c++ language to handle queries like INSERT, FIND, COUNT and RANGE.

# Types of Queries
1. INSERT x - insert x into the B+tree
2. FIND x - print YES if x is already inserted , else NO
3. COUNT x - print number of occurrences of x in B+tree
4. RANGE x y - print number of elements in range x to y ( both x and y included)

# Constraints
1. -10^9 <= x <= 10^9 and -10^9 <= y <= 10^9.
2. Number of queries will be less than 10^6.

# NOTE
For calculating degree of b+tree:
if each block has space for n keys and n+1 pointers then size occupied = 4*(n)+8*(n+1) [if keys are integer]. Let this be called "S". Thus, picking the maximum value of n such that S<=B(block size).

# Input
​ <Filename,B> as command line arguement , where each line of "filename" (name of input file) consists one of the above mentioned query. "B" is the buffer/block size.

# Output
Printing output of each command in a separate line
