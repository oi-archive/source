
# 题目描述

小 Y 是一个爱好旅行的 OIer。一天，她来到了一个新的城市。由于不熟悉那里的交通系统，她选择了坐地铁。

她发现每条地铁线路可以看成平面上的一条曲线，不同线路的交点处一定会设有换乘站![interchange-station.png](/source/loj/2323/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTAvNWEyYzk0Y2U4NTQ2NS5wbmc=.png)。通过调查得知，没有线路是环线，也没有线路与自身相交。任意两条不同的线路只会在若干个点上相交，没有重合的部分，且没有三线共点的情况。即，如图所示的情况都是不存在的：

![examples.png](/source/loj/2323/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTAvNWEyYzk0ZDRiNTZhZC5wbmc=.png)

小 Y 坐着地铁 $0$ 号线，路上依次经过了 $n$ 个换乘站。她记下了每个换乘站可以换乘的线路编号，发现每条线路与她所乘坐的线路最多只有 $2$ 个换乘站。现在小Y想知道，除掉她经过的换乘站以外，这个城市里最少有几个换乘站。只有你告诉她正确的答案，她才会答应下次带你去玩呢。


# 输入格式

**请注意本题有多组输入数据。**

输入数据的第一行是一个整数 $T$，表示输入数据的组数。接下来依次给出每组数据。

对于每组数据，第一行是一个整数 $n$，表示小Y经过的换乘站的数目。第二行为 $n$ 个用空格隔开的整数，依次表示每个换乘站的可以换乘的线路编号。这些编号都在 $1$ ~ $n$ 之内。

# 输出格式

对于每组输入数据，输出一行一个整数，表示除掉这 $n$ 个换乘站之外，最少有几个换乘站。

# 样例

#### 样例输入
```plain
4
4
1 2 1 2
8
1 2 3 4 1 2 3 4
5
5 4 3 3 5
8
1 2 3 4 1 3 2 4
```

#### 样例输出
```plain
0
0
0
1
```

#### 样例解释
对于样例的前两组数据，一种可能的最优答案如下图所示。

![sample1.png](/source/loj/2323/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTAvNWEyYzk0ZDRiNWM4Ny5wbmc=.png)

# 数据范围与提示

一共有 50 个测试点，每个测试点 2 分。你只有在答案完全正确时才能得到该测试点的全部分数，否则不得分。

对于所有测试点，以及对于样例，$1 \leqslant T \leqslant 100, 1 \leqslant n \leqslant 44$。对于每个测试点，$n$ 的范围如下表：

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $1 \leqslant n \leqslant $ | 测试点编号 | $ 1\leqslant n \leqslant $ |
|:-:|:-:|:-:|:-:|
| 1 | 2 | 26 | 32 |
| 2 | 3 | 27 | 33 |
| 3 | 4 | 28 | 33 |
| 4 | 5 | 29 | 34 |
| 5 | 6 | 30 | 34 |
| 6 | 8 | 31 | 35 |
| 7 | 9 | 32 | 35 |
| 8 | 10 | 33 | 36 |
| 9 | 11 | 34 | 36 |
| 10 | 12 | 35 | 37 |
| 11 | 13 | 36 | 37 |
| 12 | 14 | 37 | 38 |
| 13 | 15 | 38 | 38 |
| 14 | 16 | 39 | 39 |
| 15 | 17 | 40 | 39 |
| 16 | 20 | 41 | 40 |
| 17 | 22 | 42 | 40 |
| 18 | 24 | 43 | 41 |
| 19 | 26 | 44 | 41 |
| 20 | 28 | 45 | 42 |
| 21 | 30 | 46 | 43 |
| 22 | 30 | 47 | 43 |
| 23 | 31 | 48 | 43 |
| 24 | 31 | 49 | 44 |
| 25 | 32 | 50 | 44 |

<!-- Migrated from original HTML table:
<table><thead>
<tr>
<th style='text-align:center'>测试点编号</th><th style='text-align:center'>$1 \leqslant n \leqslant $ </th><th style='text-align:center'>测试点编号</th><th style='text-align:center'>$ 1\leqslant n \leqslant $ </th></tr>
</thead><tbody>
<tr>
<td style='text-align:center'>1</td><td style='text-align:center'>2</td><td style='text-align:center'>26</td><td style='text-align:center'>32</td></tr>
<tr>
<td style='text-align:center'>2</td><td style='text-align:center'>3</td><td style='text-align:center'>27</td><td style='text-align:center'>33</td></tr>
<tr>
<td style='text-align:center'>3</td><td style='text-align:center'>4</td><td style='text-align:center'>28</td><td style='text-align:center'>33</td></tr>
<tr>
<td style='text-align:center'>4</td><td style='text-align:center'>5</td><td style='text-align:center'>29</td><td style='text-align:center'>34</td></tr>
<tr>
<td style='text-align:center'>5</td><td style='text-align:center'>6</td><td style='text-align:center'>30</td><td style='text-align:center'>34</td></tr>
<tr>
<td style='text-align:center'>6</td><td style='text-align:center'>8</td><td style='text-align:center'>31</td><td style='text-align:center'>35</td></tr>
<tr>
<td style='text-align:center'>7</td><td style='text-align:center'>9</td><td style='text-align:center'>32</td><td style='text-align:center'>35</td></tr>
<tr>
<td style='text-align:center'>8</td><td style='text-align:center'>10</td><td style='text-align:center'>33</td><td style='text-align:center'>36</td></tr>
<tr>
<td style='text-align:center'>9</td><td style='text-align:center'>11</td><td style='text-align:center'>34</td><td style='text-align:center'>36</td></tr>
<tr>
<td style='text-align:center'>10</td><td style='text-align:center'>12</td><td style='text-align:center'>35</td><td style='text-align:center'>37</td></tr>
<tr>
<td style='text-align:center'>11</td><td style='text-align:center'>13</td><td style='text-align:center'>36</td><td style='text-align:center'>37</td></tr>
<tr>
<td style='text-align:center'>12</td><td style='text-align:center'>14</td><td style='text-align:center'>37</td><td style='text-align:center'>38</td></tr>
<tr>
<td style='text-align:center'>13</td><td style='text-align:center'>15</td><td style='text-align:center'>38</td><td style='text-align:center'>38</td></tr>
<tr>
<td style='text-align:center'>14</td><td style='text-align:center'>16</td><td style='text-align:center'>39</td><td style='text-align:center'>39</td></tr>
<tr>
<td style='text-align:center'>15</td><td style='text-align:center'>17</td><td style='text-align:center'>40</td><td style='text-align:center'>39</td></tr>
<tr>
<td style='text-align:center'>16</td><td style='text-align:center'>20</td><td style='text-align:center'>41</td><td style='text-align:center'>40</td></tr>
<tr>
<td style='text-align:center'>17</td><td style='text-align:center'>22</td><td style='text-align:center'>42</td><td style='text-align:center'>40</td></tr>
<tr>
<td style='text-align:center'>18</td><td style='text-align:center'>24</td><td style='text-align:center'>43</td><td style='text-align:center'>41</td></tr>
<tr>
<td style='text-align:center'>19</td><td style='text-align:center'>26</td><td style='text-align:center'>44</td><td style='text-align:center'>41</td></tr>
<tr>
<td style='text-align:center'>20</td><td style='text-align:center'>28</td><td style='text-align:center'>45</td><td style='text-align:center'>42</td></tr>
<tr>
<td style='text-align:center'>21</td><td style='text-align:center'>30</td><td style='text-align:center'>46</td><td style='text-align:center'>43</td></tr>
<tr>
<td style='text-align:center'>22</td><td style='text-align:center'>30</td><td style='text-align:center'>47</td><td style='text-align:center'>43</td></tr>
<tr>
<td style='text-align:center'>23</td><td style='text-align:center'>31</td><td style='text-align:center'>48</td><td style='text-align:center'>43</td></tr>
<tr>
<td style='text-align:center'>24</td><td style='text-align:center'>31</td><td style='text-align:center'>49</td><td style='text-align:center'>44</td></tr>
<tr>
<td style='text-align:center'>25</td><td style='text-align:center'>32</td><td style='text-align:center'>50</td><td style='text-align:center'>44</td></tr>
</tbody></table>
-->

<!-- END: Migrated markdown table -->


