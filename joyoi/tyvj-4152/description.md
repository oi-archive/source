# 

 
 # 题目背景 
<p>&ldquo;每个人都拥有一个梦，即使彼此不相同，能够与你分享，无论失败成功都会感动。爱因为在心中，平凡而不平庸，世界就像迷宫，却又让我们此刻相逢Our&nbsp;Home。&rdquo;</p> 

 
 # 题目描述 
<p>在爱的国度里有N个人，在他们的心中都有着一个爱的名单，上面记载着他所爱的人（不会出现自爱的情况）。爱是具有传递性的，即如果A爱B，B爱C，则A也爱C。</p>

<p>如果有这样一部分人，他们彼此都相爱，则他们就超越了一切的限制，用集体的爱化身成为一个爱心天使。</p>

<p>现在，我们想知道在这个爱的国度里会出现多少爱心天使。而且，如果某个爱心天使被其他所有人或爱心天使所爱则请输出这个爱心天使是由哪些人构成的，否则输出-1。</p> 

 
 # 输入格式 
<p>第1行，两个数N、M，代表爱的国度里有N个人，爱的关系有M条。</p>

<p>第2到第M+1行，每行两个数A、B，代表A爱B。</p> 

 
 # 输出格式 
<p>第1行，一个数，代表爱的国度里有多少爱心天使。</p>

<p>第2行，如果某个爱心天使被其他所有人和爱心天使所爱则请输出这个爱心天使是由哪些人构成的（从小到大排序），否则输出-1。</p> 

 
 # 提示 
<p><span style="line-height: 1.6em;">对于40%的数据&nbsp;&nbsp;&nbsp;N&lt;=10　　&nbsp;&nbsp;&nbsp;M&lt;=100</span></p>

<p>对于80%的数据&nbsp;&nbsp;&nbsp;N&lt;=100　　&nbsp;&nbsp;M&lt;=1000</p>

<p>对于100%的数据&nbsp;&nbsp;N&lt;=1000　　&nbsp;M&lt;=10000</p> 
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
<tr><td>3 3
1 2
2 1
2 3
</td><td>1
-1</td></tr><tr><td>6 7
1 2
2 3
3 2
4 2
4 5
5 6
6 4
</td><td>2
2 3</td></tr></table>
