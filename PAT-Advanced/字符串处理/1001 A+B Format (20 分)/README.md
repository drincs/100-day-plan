# 1001 A+B Format (20 分)
> Calculate a+b and output the sum in standard format -- that is, the digits must be separated into groups of three by commas (unless there are less than four digits).

> ## Input Specification:
> Each input file contains one test case. Each case contains a pair of integers a and b where −10<sup>6</sup>​​ ≤a,b≤10<sup>6</sup>​​.The numbers are separated by a space.

> ## Output Specification:
> For each test case, you should output the sum of a and b in one line. The sum must be written in the standard format.

> ## Sample Input:
> -1000000 9
> ## Sample Output:
> -999,991
## 题目大意
计算A+B,输出逗号格式（三位一组，除非数字位数小于4位数）
## 解题思路
根据输入范围可知，结果范围在7位数内<br>
计算A+B,求位数，存各位到数组。