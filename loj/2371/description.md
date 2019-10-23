
# 题目描述

**题目译自 BalticOI 2015 Day1 Network(NET)，原题面见附加文件。**  
**本题由 [HeRaNO](/user/751) 翻译，如欲转载翻译，请注明翻译者信息及转载出处。**

Byteland 政府决定让他们国家接入互联网，这样的话所有公民都能上网参加程序设计竞赛和吸猫。当建设国家主干网络时，他们让 IOI（Internet Optimists Inc.）公司把 Byteland 境内所有 $n$ 台计算机连接起来。两台计算机用网线直接相连，这样任意两台计算机就通过一系列网线相连了。

从任何意义上讲，Byteland 都不是一个富有的国家，所以为了最小化开销，Byteland 的网络拓扑结构是一棵树（即，恰好有 $n-1$ 条网线连接计算机）。然而当他们意识到这样的结构有严重的缺陷时已经太晚了。如果仅仅是一条网线断了，Byteland 的计算机就会被分离，这样的话一些计算机就不能互相通信。

为了提升 Byteland 的网络可靠性，官方决定应至少能承受一条网线坏掉的情况。你的任务是帮助 IOI 公司用最便宜的方式提升网络可靠性。给定 Byteland 的网络拓扑结构（即一棵 $n$ 个点的树），找到最少加多少条网线，使得如果任意一根网线坏掉的情况下网络还是连通的。 

# 输入格式

第一行包含一个正整数 $n$，表示 Byteland 有 $n$ 台计算机。为了表示方便，所有计算机从 $1$ 到 $n$ 编号；

接下来 $n-1$ 行，每行两个整数 $a,b$，表示 $a,b$ 计算机直接由网线相连。

# 输出格式

第一行应该输出一个整数 $k$，表示最少应该向这个网络加的网线数。接下来 $k$ 行，每行输出两个整数 $a,b$，表示 $a,b$ 计算机之间加一条网线将它们连接起来。网线顺序任意。如果有多组解，可以输出任意一组。

# 样例

#### 样例输入 1

```plain
6
1 2
2 3
2 4
5 4
6 4
```
#### 样例输出 1

```plain
2
1 5
3 6
```
#### 样例说明 1

![boi-net1.png](/source/loj/2371/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8xMC8xNi81ZGE3MjVjNzhjM2UxLnBuZw==.png)


#### 样例输入 2
```plain
8
1 2
2 3
3 4
4 5
3 6
3 7
3 8
```
#### 样例输出 2
```plain
3
1 6
5 7
8 4
```

#### 样例说明 2

![boi-net2.png](/source/loj/2371/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8xMC8xNi81ZGE3MjVjNmVlYWNhLnBuZw==.png)

# 数据范围与提示

|子任务编号|$n$|分值|
|:-:|:-:|:-:|
|$1$|$n\le 10$|$18$|
|$2$|$n\le 2\times 10^3$|$45$|
|$3$|$n\le 5\times 10^5$|$37$|

对于所有子任务，$n\ge 3,1\le a,b\le n,a\neq b$。

