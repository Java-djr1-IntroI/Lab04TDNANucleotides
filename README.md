## Java I Lab 04

Counting DNA Nucleotides

**Date assigned:** 

**Program due:**

**Points:** 

**This is an individual assignment.**

**Goals:**

1.  Use the various if and loop statements that exist

2.  Make sure that code is readable by using well named constants, variables, and proper nesting

**Lab 4**

A string is simply an ordered collection of symbols selected from some alphabet and formed into a word; 
the length of a string is the number of symbols that it contains.

An example of a length 21 DNA string (whose alphabet contains the symbols 'A', 'C', 'G', and 'T') is 
"ATGCTTCAGAAAGGTCTTACG."

Input from the keyboard: A DNA string s of length at most 1000 nt (nucleotides).

Output to the screen: The number of times that the symbols 
'A', 'C', 'G', and 'T' occur in s.

**Sample Input**
<pre>
AGCTTTTCATTCTGACTGCAACGGGCAATATGTCTCTGTGTGGATTAAAAAAAGAGTGTCTGATAGCAGC
</pre>

**Sample Output**
<pre>
A's: 20 
C's: 12 
G's: 17 
T's: 21
</pre>

Write a program that allows the user the ability to enter a DNA string and outputs the occurrences of A's, C's, G's and T's as shown above. For this assignment you will need to use two string methods charAt () and length (). Here is an example:

<pre>
String s = "ACGTT";
int i = 1;
System.out.println ("" + s.charAt (i) + s.length ());
</pre>

produces the output:

<pre>
C5
</pre>

Hopefully from this example, you can see how to use s.charAt (i) inside of a loop and check each character in the string.

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Lab04 link to accept this
        assignment as we've done before. Once accepted, code up a
        complete solution to each project specified above. Your
        complete solution is to be pushed to GitHub no later than the
        date and time specified above for your specific section. I will
        only grade your solution from the proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.  **An electronic pdf (punetidLab04DNA.pdf) 
of your program is to be emailed to ryandj@pacificu.edu**
