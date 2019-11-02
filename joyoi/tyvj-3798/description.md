# 

 
 # 题目背景 
<p>有一天，小Q梦见自己来到了理想国的幻想之乡。</p> 

 
 # 题目描述 
<p>有一天，小Q梦见自己来到了理想国的幻想之乡。幻想乡有无穷户居民，第i个家庭住在编号为i的房屋里，编号从1开始，到正无穷。</p>

<p>居民们的房屋之间有着许多种道路，其中第k种道路只连接在编号为k的倍数且在k的倍数中连续的房屋之间。例如第1种道路连接在编号为(1,2),(2,3),(3,4)&hellip;的房屋之间，而第3种道路只连接在编号为(3,6),(6,9),(9,12)&hellip;的房屋之间。</p>

<p>小Q要抓紧睡梦的时间来拜访幻想之乡中的贵人，他希望你能帮他完成这场幻想之旅。<span style="line-height: 1.6em;">他经常会从某个编号为i的房屋只走某种道路快速到达某个编号为j的房屋，比如说从编号为4的房屋走到编号为8的房屋，可以走4-&gt;5-&gt;6-&gt;7-&gt;8，也可以走4-&gt;6-&gt;8，甚至可以走4-&gt;8一步到达目的地。</span></p>

<p><span style="line-height: 1.6em;">他很好奇，如果他的起点房屋的编号是不大于n的，终点房屋的编号是不大于m的，对于所有可能的起点与终点，他最少会走多少条路，注意他的移动只会选择一种道路。</span></p>

<p><span style="line-height: 1.6em;">为了避免精度误差，他希望你能告诉他所有可能的起点与终点所对应的经过的最少边数之和。</span></p>

<p><span style="line-height: 1.6em;">由于这个数可能超过10^18，但是不会很大，所以你只需要求出它对两个质数10^9+7和10^9+9的模值即可，小Q的数学很好，他会算出原来的答案。</span></p> 

 
 # 输入格式 
<p>第一行一个正整数T，表示小Q有T组好奇的问题。</p>

<p>接下来是T组问题，每组问题占一行，共两个正整数n,&nbsp;m，空格隔开。</p> 

 
 # 输出格式 
<p>共T行，每行两个空格隔开的整数，表示每组问题分别模10^9+7和10^9+9的答案。</p> 

 
 # 提示 
<h4>数据范围</h4>

<p>前20%的数据&nbsp;n,&nbsp;m&nbsp;&lt;=&nbsp;10^3</p>

<p>前60%的数据&nbsp;T&nbsp;&lt;=&nbsp;100,&nbsp;n,&nbsp;m&nbsp;&lt;=&nbsp;10^4</p>

<p>前60%的数据中混杂着20%的数据&nbsp;n&nbsp;=&nbsp;m</p>

<p>100%的数据&nbsp;T&nbsp;&lt;=&nbsp;1000,&nbsp;n,&nbsp;m&nbsp;&lt;=&nbsp;2*10^6</p>

<h4>来源</h4>

<p>tangjz</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>2
3 3
2 4
</td><td>8 8
9 9
</td></tr></table>
