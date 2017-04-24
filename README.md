# lab4

#
A.

第一個function: double average(double * n1, double & n2)

00000000004006cd T _Z7averagePdRd

第二個function: int average(int n1, float n2)

000000000040070d T _Z7averageif

main function

0000000000400735 T main

B.

1 8

4 8

4 8

8 8


First line shows the size of a, *pa
Since "a" is char type ,is only need 1 byte.
In general,pointer's size is fixed(except function pointers),and my computer is 64bits ,so *pa is 8 bytes.
And the rest pointers of other types are also the same size.
For second line, type of integer is 4 bytes.
Third line, float type need 4bytes.
Last line, double type is 8byte which is two times as many bytes as float.
