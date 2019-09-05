# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Turkey 买了 36 个卡包，并且把他们排列成6×6的阵型准备开包。左上角的包是(0,0)，右下角为(5,5)。为了能够开到更多的金色普通卡，Turkey 会为每个包添加1 −5个玄学值，每个玄学值可以是1 − 30中的一个整数。但是不同的玄学值会造成不同的欧气加成，具体如下：
</p>
<p>
1、同一个卡包如果有两个相同的玄学值会有无限大的欧气加成。
</p>
<p>
2、同一个卡包如果有两个相邻的玄学值会有A点欧气加成。
</p>
<p>
3、相邻的两个卡包如果有相同的玄学值会有B点欧气加成。
</p>
<p>
4、相邻的两个卡包如果有相邻的玄学值会有C点欧气加成。
</p>
<p>
5、距离为2的卡包如果有相同的玄学值会有D点欧气加成。
</p>
<p>
6、距离为2的卡包如果有相邻的玄学值会有E点欧气加成。
</p>
<p>
以上的所有加成是每存在一个符合条件的就会加一次，如一包卡有1,2,3的玄学值就会加两次。
</p>
<p>
但 是 ， 玄 学 值 是 个 不 可 控 的 东 西 ， 即 使 是  Turkey 也 只 能 自 己 决 定2,2 , 2,3 , 3,2 , (3,3)这几包卡的玄学值。为了能够抽到更多的金色普通卡，Turkey
</p>
<p>
想知道自己能够获得的最少的欧气加成是多少。注意你只能修改玄学值，不能修改玄学值的个数。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入的第一行有5个整数A,B,C,D,E。
</p>
<p>
接下去有6×6的代表初始的玄学值。
</p>
<p>
每个玄学值为[n:a1,a2,a3,...,an]的描述形式。
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个整数代表答案。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5 4 3 2 1
</p>

<p>
[1:1][1:2][1:3][1:4][1:5][1:6]
</p>

<p>
[1:1][1:2][1:3][1:4][1:5][1:6]
</p>

<p>
[1:1][1:2][5:1,2,3,4,5][5:1,2,3,4,5][1:5][1:6]
</p>

<p>
[1:1][1:2][5:1,2,3,4,5][5:1,2,3,4,5][1:5][1:6]
</p>

<p>
[1:1][1:2][1:3][1:4][1:5][1:6]
</p>

<p>
[1:1][1:2][1:3][1:4][1:5][1:6]
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>250</pre>
<h3>
【提示】
</h3>
<p>
对于100%的数据，1 ≤ A,B,C,D,E ≤ 100,1 ≤ n ≤ 5,1 ≤ ai ≤ 30。有部分分。
</p>
<h3>
【来源】
</h3>
<p>
qbxt 2017.10.7 t3
</p>