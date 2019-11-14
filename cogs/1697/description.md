# 题目描述


<h3>
【题目描述】
</h3>
<p>
有一个湖，他的周围都是城市，每个城市都只和他相邻的两个城市有道路相连。假设有n个城市，编号1-n，公路是双向的，公路有时候是好的，有时候是坏的，现在询问你两个城市是否可以互相到达。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个数，一个2&lt;=n&lt;=100000  和 1&lt;=m&lt;=100000，分别代表城市数目和询问次数；接下来m行，每一行三个数f，a，b。f=0时，如果公路a，b之间的道路之前是好的，现在就变成坏的，如果之前是坏的，现在就变成好的。f=1时，询问a，b两个城市是否可以互相到达。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一个f=1的询问，能到达输出“YES”，否则输出&#34;NO&#34;.
</p>
<h3>
【样例输入】
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">5 10</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">1 2 5</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">0 4 5</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">1 4 5</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">0 2 3</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">1 3 4</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">1 1 3</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">0 1 2</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">0 2 3</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">1 2 4</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">1 2 5</span>
</h3>
<h3>
【样例输出】
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">YES</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">YES</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">YES</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">NO</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">YES</span>
</h3>
<h3>
<span style="font-family:monospace;font-size:15px;font-weight:normal;line-height:16px;white-space:pre-wrap;background-color:#F5F5F5;">NO</span>
</h3>
<h3>
【提示】
</h3>
<p>
30%   2&lt;=n,m&lt;=100
</p>
<p>
50%   2&lt;=n,m&lt;=10000
</p>
<p>
100%  2&lt;=n,m&lt;=100000
</p>
<h3>
【来源】
</h3>
<p>
@高哥
</p>
