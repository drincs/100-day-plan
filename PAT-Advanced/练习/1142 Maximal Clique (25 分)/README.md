# 1142 Maximal Clique (25 分)  
> A clique is a subset of vertices of an undirected graph such that every two distinct vertices in the clique are adjacent. A maximal clique is a clique that cannot be extended by including one more adjacent vertex. (Quoted from https://en.wikipedia.org/wiki/Clique_(graph_theory))  
> Now it is your job to judge if a given subset of vertices can form a maximal clique.  
> ## Input Specification:  
> Each input file contains one test case. For each case, the first line gives two positive integers Nv (≤ 200), the number of vertices in the graph, and Ne, the number of undirected edges. Then Ne lines follow, each gives a pair of vertices of an edge. The vertices are numbered from 1 to Nv.  
> After the graph, there is another positive integer M (≤ 100). Then M lines of query follow, each first gives a positive number K (≤ Nv), then followed by a sequence of K distinct vertices. All the numbers in a line are separated by a space.  
> ## Output Specification:  
> For each of the M queries, print in a line Yes if the given subset of vertices can form a maximal clique; or if it is a clique but not a maximal clique, print Not Maximal; or if it is not a clique at all, print Not a Clique.  
> ## Sample Input:
```
8 10
5 6
7 8
6 4
3 6
4 5
2 3
8 2
2 7
5 3
3 4
6
4 5 4 3 6
3 2 8 7
2 2 3
1 1
3 4 3 6
3 3 2 1
```
> ## Sample Output:
```
Yes
Yes
Yes
Yes
Not Maximal
Not a Clique
```
## 完成时间

## 题目大意
```
    1 2 3 4 5 6 7 8
1
2     1 1       1 1
3     1   1 1 1 
4       1   1 1
5       1 1   1
6       1 1 1
7     1           1
8               1
```
## 解题思路
```
clique定义：每两个不同的顶点在clique中是连通的 连通子图
maximal clique定义：添加连通的顶点不能扩展该集合。
```