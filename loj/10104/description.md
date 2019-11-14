
# 题目描述

**原题来自：POI 2008**

Byteotia 城市有 $n$ 个城镇，$m$ 条双向道路。每条道路连接两个不同的城镇，没有重复的道路，所有城镇连通。  
输出 $n$ 个数，代表如果把与第 $i$ 个点连接的所有边去掉，将有多少对点不能互通。

# 输入格式

输入 $n,m$ 及 $m$ 条边。

# 输出格式

输出 $n$ 个数，代表如果把第 $i$ 个点连接的所有边去掉，将有多少对点不能互通。

# 样例

#### 样例输入
```plain
5 5
1 2
2 3
1 3
3 4
4 5
```

#### 样例输出
```plain
8
8
16
14
8
```

#### 样例说明
![blo](/source/loj/10104/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vZUR0OHcyOTBvd3RhdG1DamFkME8weXdrL3NpdGUvaW1hZ2VzL09JMTUvYmxvemFkMS5naWY=.gif)

# 数据范围与提示

$n\le 10^5, m\le 5×10^5$。

