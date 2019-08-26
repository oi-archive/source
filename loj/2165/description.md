
# 题目描述

**译自 POI 2011 Round 3. Day 0. A「[Dynamite](https://szkopul.edu.pl/problemset/problem/Xg9hVYries5K7yMcyZYI4NLc/site/?key=statement)」**

The Byteotian Cave is composed of $ n $ chambers and $ n-1 $ corridors that connect them. For every pair of chambers there is unique way to move from one of them to another without leaving the cave. Dynamite charges are set up in certain chambers. A fuse is laid along every corridor. In every chamber the fuses from the adjacent corridors meet at one point, and are further connected to the dynamite charge if there is one in the chamber. It takes exactly one unit of time for the fuse between two neighbouring chambers to burn, and the dynamite charge explodes in the instant that fire reaches the chamber it is inside.

We would like to light the fuses in some $ m $ chambers (at the joints of fuses) in such a way that all the dynamite charges explode in the shortest time possible since the fuses are lit. Write a program that will determine the minimum such time possible.


# 输入格式

The first line of the standard input holds two integers $ n $ and $ m $ ($ 1 \le m \le n \le 300000$), separated by a single space, that denote, respectively, the number of chambers in the cave and the number of chambers in which fire can be set to the fuses. The chambers are numbered from $ 1 $ to $ n $. The next line contains $ n $ integers $ d_1, d_2, \ldots, d_n $ ($ d_i \in \{0, 1\} $), separated by single spaces. If $ d_i = 1 $, then there is dynamite in the $ i $-th chamber, and if $ d_i = 0$, there is none. The following $ n-1 $ lines specify the corridors of the cave. Each of them holds two integers $ a $, $ b $ ($ 1 \le a \lt b \le n $), separated by a single space, denoting that there is a corridor connecting the chambers $ a $ and $ b $. Every corridor appears exactly once in the description.

You may assume that in tests worth 10% of the points it holds additionally that $ n \le 10 $, while in tests worth 40% of the points it holds that $ n \le 1000 $.

# 输出格式

The first and only line of the standard output should hold a single integer, equal to the minimum time it takes from lighting the fuses to the explosion of all the charges.

# 样例

For the input data:
```plain
7 2
1 0 1 1 0 1 1
1 3
2 3
3 4
4 5
5 6
5 7
```
the correct result is:
```plain
1
```
![](source/loj/2165/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA0LzE5LzU4ZjZiOWE0N2UyOGQuZ2lm.gif)

Explanation of the example: We light the fuses in chambers 3 and 5. The charge in chamber 3 explodes at time zero, and the charges in chambers 1, 4, 6 and 7 explode after a single time unit.

# 数据范围与提示

Task author: Jacek Tomasiewicz.

