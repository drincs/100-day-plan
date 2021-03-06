# 1029 Median (25 分)
> $~~~~$ Given an increasing sequence S of N integers, the median is the number at the middle position. For example, the median of S1 = { 11, 12, 13, 14 } is 12, and the median of S2 = { 9, 10, 15, 16, 17 } is 15. The median of two sequences is defined to be the median of the nondecreasing sequence which contains all the elements of both sequences. For example, the median of S1 and S2 is 13.

> $~~~~$ Given two increasing sequences of integers, you are asked to find their median.

> ## Input Specification:  
> $~~~~$ Each input file contains one test case. Each case occupies 2 lines, each gives the information of a sequence. For each sequence, the first positive integer N (≤2×10<sup>5</sup>) is the size of that sequence. Then N integers follow, separated by a space. It is guaranteed that all the integers are in the range of long int.

> ## Output Specification:
> $~~~~$ For each test case you should output the median of the two given sequences in a line.

> ## Sample Input:
```
4 11 12 13 14
5 9 10 15 16 17
```
> ## Sample Output:
```
13
```
## 题目大意
给定两个递增序列,求中位数。

## 解题思路
根据两个序列的总长度，求出中位数所在下标，依次判断。  
第一次得分19，原因是忘记考虑两个序列长度不一致的原因，最后用时30分钟。