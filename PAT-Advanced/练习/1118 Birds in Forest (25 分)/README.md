# 1118 Birds in Forest (25 分)  
> Some scientists took pictures of thousands of birds in a forest. Assume that all the birds appear in the same picture belong to the same tree. You are supposed to help the scientists to count the maximum number of trees in the forest, and for any pair of birds, tell if they are on the same tree.  
> ## Input Specification:  
> Each input file contains one test case. For each case, the first line contains a positive number N (≤10<sup>4</sup>) which is the number of pictures. Then N lines follow, each describes a picture in the format:  
> K B<sub>1</sub> B<sub>2</sub> ... B<sub>K</sub> where K is the number of birds in this picture, and B<sub>i</sub> 's are the indices of birds. It is guaranteed that the birds in all the pictures are numbered continuously from 1 to some number that is no more than 10<sup>4</sup> .  
> After the pictures there is a positive number Q (≤10<sup>4</sup>) which is the number of queries. Then Q lines follow, each contains the indices of two birds.  
> ## Output Specification:  
> For each test case, first output in a line the maximum possible number of trees and the number of birds. Then for each query, print in a line Yes if the two birds belong to the same tree, or No if not.  
> ## Sample Input:
```
4
3 10 1 2
2 3 4
4 1 5 7 8
3 9 6 4
2
10 5
3 7
```
> ## Sample Output:
```
2 10
Yes
No
```