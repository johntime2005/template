# Templates

这个仓库总结了部分算法竞赛模板  
但困于个人能力限制，本仓库只有提高组级别的模板  
而且个别模板质量并不高，也希望各位多多包涵  
如果你有更好的模板或者想法，我很乐意合并你的请求  

另外，本仓库中大部分模板来自 `AcWing算法课` 和 `算法进阶指南`  
少部分来自网络或个人代码，感谢Ta们对我编程学习的帮助  

以下是目录:
## [基本算法](./1_基本算法.md)

* [基本算法](./1_基本算法.md#基本算法)
    * [位运算](./1_基本算法.md#位运算)
        * [快速幂](./1_基本算法.md#快速幂)
        * [龟速乘](./1_基本算法.md#龟速乘)
        * [快速乘](./1_基本算法.md#快速乘)
    * [排序算法](./1_基本算法.md#排序算法)
        * [1快速排序](./1_基本算法.md#1快速排序)
        * [2归并排序](./1_基本算法.md#2归并排序)
    * [二分](./1_基本算法.md#二分)
        * [整数二分算法模板](./1_基本算法.md#整数二分算法模板)
        * [1区间[l,r]被划分成[l,mid]和[mid+1,r]时使用](./1_基本算法.md#1区间[l,r]被划分成[l,mid]和[mid+1,r]时使用)
        * [2区间[l,r]被划分成[l,mid-1]和[mid,r]时使用](./1_基本算法.md#2区间[l,r]被划分成[l,mid-1]和[mid,r]时使用)
        * [3浮点数二分算法模板](./1_基本算法.md#3浮点数二分算法模板)
    * [高精度](./1_基本算法.md#高精度)
        * [1加法](./1_基本算法.md#1加法)
        * [2减法](./1_基本算法.md#2减法)
        * [3乘法](./1_基本算法.md#3乘法)
        * [4除法](./1_基本算法.md#4除法)
    * [前缀和差分](./1_基本算法.md#前缀和差分)
        * [1一维前缀和](./1_基本算法.md#1一维前缀和)
        * [2二维前缀和](./1_基本算法.md#2二维前缀和)
        * [3一维差分](./1_基本算法.md#3一维差分)
        * [4二维差分](./1_基本算法.md#4二维差分)
    * [双指针算法](./1_基本算法.md#双指针算法)
    * [离散化与逆序对](./1_基本算法.md#离散化与逆序对)
        * [1哈希](./1_基本算法.md#1哈希)
        * [2二分](./1_基本算法.md#2二分)
    * [文件读写](./1_基本算法.md#文件读写)
    * [快读](./1_基本算法.md#快读)

## [数据结构](./2_数据结构.md)

* [数据结构](./2_数据结构.md#数据结构)
    * [链表](./2_数据结构.md#链表)
        * [1单链表](./2_数据结构.md#1单链表)
        * [2双链表](./2_数据结构.md#2双链表)
    * [栈](./2_数据结构.md#栈)
    * [队列](./2_数据结构.md#队列)
    * [单调队列](./2_数据结构.md#单调队列)
    * [单调栈](./2_数据结构.md#单调栈)
    * [KMP](./2_数据结构.md#KMP)
    * [Trie树](./2_数据结构.md#Trie树)
    * [并查集](./2_数据结构.md#并查集)
    * [堆](./2_数据结构.md#堆)
    * [hash表](./2_数据结构.md#hash表)
        * [1开放寻址法](./2_数据结构.md#1开放寻址法)
        * [2拉链法](./2_数据结构.md#2拉链法)
        * [3字符串哈希](./2_数据结构.md#3字符串哈希)
    * [C++STL](./2_数据结构.md#C++STL)
    * [线段树](./2_数据结构.md#线段树)
    * [树状数组](./2_数据结构.md#树状数组)

## [图论I](./3_图论I.md)

* [图论I](./3_图论I.md#图论I)
    * [有向图和无向图](./3_图论I.md#有向图和无向图)
    * [存图](./3_图论I.md#存图)
    * [图的深度优先搜索](./3_图论I.md#图的深度优先搜索)
    * [图的宽度优先搜索](./3_图论I.md#图的宽度优先搜索)
    * [拓扑排序](./3_图论I.md#拓扑排序)
        * [度数](./3_图论I.md#度数)
    * [最短路](./3_图论I.md#最短路)
        * [单源最短路](./3_图论I.md#单源最短路)
            * [所有边权都是正数](./3_图论I.md#所有边权都是正数)
                * [朴素Dijkstra算法](./3_图论I.md#朴素Dijkstra算法)
                * [堆优化的Dijkstra算法](./3_图论I.md#堆优化的Dijkstra算法)
            * [存在负权边](./3_图论I.md#存在负权边)
                * [Bellman-Ford](./3_图论I.md#Bellman-Ford)
                * [SPFA](./3_图论I.md#SPFA)
        * [多源汇最短路](./3_图论I.md#多源汇最短路)
            * [Floyd算法](./3_图论I.md#Floyd算法)
    * [最小生成树](./3_图论I.md#最小生成树)
        * [Prim](./3_图论I.md#Prim)
            * [朴素版Prim](./3_图论I.md#朴素版Prim)
            * [堆优化Prim](./3_图论I.md#堆优化Prim)
        * [Kruskal](./3_图论I.md#Kruskal)
    * [二分图](./3_图论I.md#二分图)
        * [染色法](./3_图论I.md#染色法)
        * [匈牙利算法](./3_图论I.md#匈牙利算法)

## [数学知识](./4_数学知识.md)

* [数学知识](./4_数学知识.md#数学知识)
    * [数论](./4_数学知识.md#数论)
        * [试除法判定质数](./4_数学知识.md#试除法判定质数)
        * [分解质因数](./4_数学知识.md#分解质因数)
        * [筛质数](./4_数学知识.md#筛质数)
        * [试除法求约数](./4_数学知识.md#试除法求约数)
        * [约数个数](./4_数学知识.md#约数个数)
        * [约数之和](./4_数学知识.md#约数之和)
        * [最大公约数](./4_数学知识.md#最大公约数)
    * [快速幂](./4_数学知识.md#快速幂)
        * [快速幂求逆元](./4_数学知识.md#快速幂求逆元)
        * [线性逆元](./4_数学知识.md#线性逆元)
    * [拓展欧几里得](./4_数学知识.md#拓展欧几里得)
        * [线性同余方程](./4_数学知识.md#线性同余方程)
    * [中国剩余定理](./4_数学知识.md#中国剩余定理)
    * [组合计数](./4_数学知识.md#组合计数)
    * [高斯消元](./4_数学知识.md#高斯消元)
    * [简单博弈论](./4_数学知识.md#简单博弈论)
    * [容斥原理](./4_数学知识.md#容斥原理)
    * [拓展欧拉定理](./4_数学知识.md#拓展欧拉定理)

## [动态规划](./5_动态规划.md)

* [背包问题](./5_动态规划.md#背包问题)
    * [01背包问题](./5_动态规划.md#01背包问题)
    * [完全背包](./5_动态规划.md#完全背包)
    * [多重背包](./5_动态规划.md#多重背包)
    * [分组背包](./5_动态规划.md#分组背包)
* [数位DP](./5_动态规划.md#数位DP)
* [线性DP](./5_动态规划.md#线性DP)
    * [数字三角形](./5_动态规划.md#数字三角形)
    * [最长上升子序列](./5_动态规划.md#最长上升子序列)
    * [最长公共子序列](./5_动态规划.md#最长公共子序列)
    * [区间DP](./5_动态规划.md#区间DP)

## [网络流初步](./6_网络流初步.md)

* [网络流初步](./6_网络流初步.md#网络流初步)
    * [EK求最大流](./6_网络流初步.md#EK求最大流)
    * [dinic求最大流](./6_网络流初步.md#dinic求最大流)
    * [点分裂](./6_网络流初步.md#点分裂)

## [图论II](./7_图论II.md)

* [图论II](./7_图论II.md#图论II)
    * [SPFA差分约束与判负环](./7_图论II.md#SPFA差分约束与判负环)
    * [LCA](./7_图论II.md#LCA)
        * [倍增](./7_图论II.md#倍增)
        * [树链剖分](./7_图论II.md#树链剖分)
    * [有向图强连通分量SCC](./7_图论II.md#有向图强连通分量SCC)
    * [无向图的双连通分量](./7_图论II.md#无向图的双连通分量)
        * [边双连通分量E-DCC](./7_图论II.md#边双连通分量E-DCC)
        * [点双连通分量V-DCC](./7_图论II.md#点双连通分量V-DCC)
    * [欧拉回路与欧拉路径](./7_图论II.md#欧拉回路与欧拉路径)

## [搜索](./8_搜索.md)

* [搜索](./8_搜索.md#搜索)
    * [指数型](./8_搜索.md#指数型)
    * [组合型](./8_搜索.md#组合型)
    * [排列型](./8_搜索.md#排列型)

