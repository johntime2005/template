# Templates

## [基本算法](./1_基本算法.md)

* [基本算法](./1_基本算法.md#基本算法)
    * [位运算](./1_基本算法.md#位运算)
        * [快速幂](./1_基本算法.md#快速幂)
        * [龟速乘](./1_基本算法.md#龟速乘)
        * [快速乘](./1_基本算法.md#快速乘)
    * [递归与搜索](./1_基本算法.md#递归与搜索)
        * [指数型](./1_基本算法.md#指数型)
        * [组合型](./1_基本算法.md#组合型)
        * [排列型](./1_基本算法.md#排列型)
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
    * [离散化&逆序对](./1_基本算法.md#离散化&逆序对)
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
        * [1.开放寻址法](./2_数据结构.md#1.开放寻址法)
        * [2.拉链法](./2_数据结构.md#2.拉链法)
        * [3.字符串哈希](./2_数据结构.md#3.字符串哈希)
    * [C++STL](./2_数据结构.md#C++STL)
    * [线段树](./2_数据结构.md#线段树)
    * [树状数组](./2_数据结构.md#树状数组)

## [搜索与图论](./3_搜索与图论.md)

* [搜索与图论](./3_搜索与图论.md#搜索与图论)
    * [搜索](./3_搜索与图论.md#搜索)
        * [dfs](./3_搜索与图论.md#dfs)
        * [bfs](./3_搜索与图论.md#bfs)
    * [图](./3_搜索与图论.md#图)
        * [有向图和无向图](./3_搜索与图论.md#有向图和无向图)
        * [存图](./3_搜索与图论.md#存图)
        * [图的深度优先搜索](./3_搜索与图论.md#图的深度优先搜索)
        * [图的宽度优先搜索](./3_搜索与图论.md#图的宽度优先搜索)
        * [拓扑排序](./3_搜索与图论.md#拓扑排序)
            * [度数](./3_搜索与图论.md#度数)
        * [最短路](./3_搜索与图论.md#最短路)
            * [单源最短路](./3_搜索与图论.md#单源最短路)
                * [所有边权都是正数](./3_搜索与图论.md#所有边权都是正数)
                    * [朴素Dijkstra算法](./3_搜索与图论.md#朴素Dijkstra算法)
                    * [堆优化的Dijkstra算法](./3_搜索与图论.md#堆优化的Dijkstra算法)
                * [存在负权边](./3_搜索与图论.md#存在负权边)
                    * [Bellman-Ford](./3_搜索与图论.md#Bellman-Ford)
                    * [SPFA](./3_搜索与图论.md#SPFA)
            * [多源汇最短路](./3_搜索与图论.md#多源汇最短路)
                * [Floyd算法](./3_搜索与图论.md#Floyd算法)
        * [最小生成树](./3_搜索与图论.md#最小生成树)
            * [Prim](./3_搜索与图论.md#Prim)
                * [朴素版Prim](./3_搜索与图论.md#朴素版Prim)
                * [堆优化Prim](./3_搜索与图论.md#堆优化Prim)
            * [Kruskal](./3_搜索与图论.md#Kruskal)
        * [二分图](./3_搜索与图论.md#二分图)
            * [染色法](./3_搜索与图论.md#染色法)
            * [匈牙利算法](./3_搜索与图论.md#匈牙利算法)

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
    * [闫式DP分析法](./5_动态规划.md#闫式DP分析法)
    * [01背包问题](./5_动态规划.md#01背包问题)
        * [分析](./5_动态规划.md#分析)
        * [code](./5_动态规划.md#code)
    * [完全背包](./5_动态规划.md#完全背包)
        * [分析](./5_动态规划.md#分析)
        * [code](./5_动态规划.md#code)
    * [多重背包](./5_动态规划.md#多重背包)
        * [分析](./5_动态规划.md#分析)
        * [code](./5_动态规划.md#code)
    * [分组背包](./5_动态规划.md#分组背包)
        * [分析](./5_动态规划.md#分析)
        * [code](./5_动态规划.md#code)

## [网络流初步](./6_网络流初步.md)

* [网络流初步](./6_网络流初步.md#网络流初步)
    * [源点，汇点](./6_网络流初步.md#源点，汇点)
    * [流网络](./6_网络流初步.md#流网络)
    * [可行流](./6_网络流初步.md#可行流)
    * [最大流](./6_网络流初步.md#最大流)
    * [残留网络](./6_网络流初步.md#残留网络)
    * [割](./6_网络流初步.md#割)
    * [集合X,Y的流量](./6_网络流初步.md#集合X,Y的流量)
    * [最大流最小割定理](./6_网络流初步.md#最大流最小割定理)
    * [EK求最大流](./6_网络流初步.md#EK求最大流)
    * [dinic求最大流](./6_网络流初步.md#dinic求最大流)
    * [点分裂](./6_网络流初步.md#点分裂)

## [图论II](./7_图论II.md)

* [图论II](./7_图论II.md#图论II)
    * [SPFA差分约束&判负环](./7_图论II.md#SPFA差分约束&判负环)
    * [LCA](./7_图论II.md#LCA)
        * [倍增](./7_图论II.md#倍增)
        * [树链剖分](./7_图论II.md#树链剖分)
    * [有向图强连通分量](./7_图论II.md#有向图强连通分量)
        * [tarjan](./7_图论II.md#tarjan)

