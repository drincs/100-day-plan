# 1108 Finding Average (20 分)  
> The basic task is simple: given N real numbers, you are supposed to calculate their average. But what makes it complicated is that some of the input numbers might not be legal. A legal input is a real number in [−1000,1000] and is accurate up to no more than 2 decimal places. When you calculate the average, those illegal numbers must not be counted in.  
> ## Input Specification:  
> Each input file contains one test case. For each case, the first line gives a positive integer N (≤100). Then N numbers are given in the next line, separated by one space.  
> ## Output Specification:  
> For each illegal input number, print in a line ERROR: X is not a legal number where X is the input. Then finally print in a line the result: The average of K numbers is Y where K is the number of legal inputs and Y is their average, accurate to 2 decimal places. In case the average cannot be calculated, output Undefined instead of Y. In case K is only 1, output The average of 1 number is Y instead.  
> ## Sample Input 1:
```
7
5 -3.2 aaa 9999 2.3.4 7.123 2.35
```
> ## Sample Output 1:
```
ERROR: aaa is not a legal number
ERROR: 9999 is not a legal number
ERROR: 2.3.4 is not a legal number
ERROR: 7.123 is not a legal number
The average of 3 numbers is 1.38
```
> ## Sample Input 2:
```
2
aaa -9999
```
> ## Sample Output 2:
```
ERROR: aaa is not a legal number
ERROR: -9999 is not a legal number
The average of 0 numbers is Undefined
```
## 题目大意
```
查找平均数：
给定N个实数，计算平均值。
输入可能非法
合法输入[-1000,1000]
不超过2位小数
```
## 解题思路
```
匹配合法输入字符串
1、第一位为正负号或数字
2、小数点前数字不得大于1000
3、等于1000不得有小数部分
4、小数点后仅能为2位数字

```