# 题目描述


<p>
<br/>
</p>
<h3>
usaco/agrinet描述
</h3>
<p>
<br/>
</p>
<div>
<div>
<div>
     农民约翰被选为他们镇的镇长！他其中一个竞选承诺就是在镇上建立起互联网，并连接到所有的场。当然，他需要你的帮助。<br/>
     约翰已经给他的农场安排了一条高速的网络线路，他想把这条线路共享给其他农场。为了用最小的消费，他想铺设最短的光纤去连接所有的农场。<br/>
     你将得到一份各农场之间连接费用的列表，你必须找出能连接所有农场并所用光纤最短的方案。<br/>
每两个农场间的距离不会超过100000
</div>
<div>
 
</div>
<div>
</div>
<div>
格式
</div>
<div>
<h2>
PROGRAM NAME: agrinet
</h2>
</div>
<div>
<h3>
INPUT FORMAT:(file agrinet.in)
</h3>
</div>
<div>
<table border="1">
<tbody>
<tr>
<td>
第一行：
</td>
<td>
农场的个数，N（3&lt;=N&lt;=100）。
</td>
</tr>
<tr>
<td>
第二行..结尾:
</td>
<td>
后来的行包含了一个N*N的矩阵,表示每个农场之间的距离。理论上，他们是N行，每行由N个用空格分隔的数组成，实际上，他们限制在80个字符，因此，某些行会紧接着另一些行。当然，对角线将会是0，因为不会有线路从第i个农场到它本身。
</td>
</tr>
</tbody>
</table>
</div>
<div>
 
</div>
<div>
<h3>
OUTPUT FORMAT:(file agrinet.out)
</h3>
</div>
<div>
<p>
只有一个输出，其中包含连接到每个农场的光纤的最小长度。
</p>
</div>
<div>
<h5>
SAMPLE INPUT
</h5>
<div>
(file agrinet.in)
</div>
</div>
<div>
4<br/>
0 4 9 21<br/>
4 0 8 17<br/>
9 8 0 16<br/>
21 17 16 0
</div>
<div>
<h5>
SAMPLE OUTPUT
</h5>
<div>
(file agrinet.out)
</div>
</div>
<div>
<p>
28
</p>
</div>
</div>
</div>
<p>
<br/>
</p>
