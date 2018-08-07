# B_plus_tree
Implementation of B+ tree in c++ language to handle queries like INSERT, FIND, COUNT and RANGE.

# Types of Queries
1. INSERT x - insert x into the B+tree
2. FIND x - print YES if x is already inserted , else NO
3. COUNT x - print number of occurrences of x in B+tree
4. RANGE x y - print number of elements in range x to y ( both x and y included)

# Constraints
1. -10^9 <= x <= 10^9 and -10^9 <= y <= 10^9.
2. Number of queries will be less than 10^6.

_NOTE_:
1. M denotes the number of buffers and B denotes the buffer size (M>=2 and M*B<=10^6)
2. Out of the M buffers, M-1 Buffers will be used as input buffers (which will hold the records from the input file), 1 buffer will be used as output buffer (holds the distinctrecords).
3. If the output buffer gets filled, it should be flushed to the output. If the input buffers get empty, next chunk of records should be read from the input file.

# Input
​ <Filename,M,B> as command line arguement , where 'filename' is the name of the input file containing integer x.

# Output
After reading every line (call it record), If record is not inserted into data structure, print it and
insert it into data structure.

