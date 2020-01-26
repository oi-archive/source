
# 题目描述

**译自 POI 2011 Round 2. Day 2. B「[Temperature](https://szkopul.edu.pl/problemset/problem/WePkBWRjS5vpsqQxi9TldHB1/site/?key=statement)」**

Byteotia 气象台（BIM）每天测量气温。整个测量过程都是自动化的，并且结果可以立即打印出来。但不幸的是，打印机的墨水早就干了……但在最近 Byteotia 气象协会（BOM）要求得到气温数据的时候，BIM 的职工才发现这个问题。

一名热心的实习生 Byteasar 拯救了这一天，因为他系统地记录了 BIM 大楼南北外墙上安装的两个家用酒精温度计报告的温度。几十年前，由多位 BIM 的职工确定，建筑物南壁上的温度计报告的温度绝不会低于实际温度，而建筑物北壁上的温度计所报告的温度绝不会高于实际温度。因此，即使不知道每天的确切温度是多少，但至少知道温度范围。

幸运的是对于在场的所有人（可能你和 Byteasar 没在现场），BOM 没要确切的温度数值。他们只想知道气温不下降的最长时间（即，对于一段连续记录的气温，这一天的气温不低于前一天的）。实际上，BIM 里的老员工十分清楚 BOM 想让这段时间越长越好。为了掩饰打印机没墨的疏忽，他坚持让 Byteasar 求出气温最长**可能**不降的时间。这个任务不太是 Byteasar 实习期要做的，他确实也不知道怎么解决。他请你帮他写个程序求出这个最长时间。

# 输入格式

第一行包含一个整数 $n$，表示 Byteasar 记录了 $n$ 天的气温；

接下来 $n$ 行，每行表示一天的气温，包含两个整数 $x,y$，分别表示每天可能的最低气温和最高气温。

# 输出格式

输出一行一个整数，表示气温最长可能不降的时间（单位：天）。

# 样例

#### 样例输入
```plain
6
6 10
1 5
4 8
2 5
6 8
3 5
```
#### 样例输出
```plain
4
```
#### 样例说明
![](/source/loj/2164/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vV2VQa0JXUmpTNXZwc3FReGk5VGxkSEIxL3NpdGUvaW1hZ2VzL09JMTgvdGVtLmdpZg==.gif)


# 数据范围与提示

对于全部数据，$1\le n\le 10^6,-10^9\le x\le y\le 10^9$。

对于 $50$ 分的数据，$-50\le x\le y\le 50$。

Task author: Jacek Tomasiewicz.

