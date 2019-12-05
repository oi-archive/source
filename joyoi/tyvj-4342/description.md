# 

 
 # 题目描述 
<div class="colorize-content">
<p>小新最喜欢的运动就是睡觉了，因为睡眠是精力恢复的重要保证。每次小新睡醒，他的脑海里总会浮现出一些奇怪的想法。某天醒来，他突然想到一个问题：</p>

<p>对于一个长度为N的整数序列：A[1],A[2],...,A[N]。如果我们定义它的一个长度为M的K邻子序列&nbsp;为:A[P1],A[P2],...,A[PM];其中满足1&lt;=K&lt;N,1&lt;=P1&lt;P2&lt;...&lt;PM&lt;&nbsp;N且P2-P1=P3-P2=...=PM-P(M-1)=K<br />
（注意，M=1，即子序列只包含一个数时，也认为它是一个合法的K邻子序列）。</p>

<p>S(K)表示给定序列中的一个和最大的K邻子序列的和。小新想知道这些S(1),S(2),...,S(N-1)中的最大值是多少，你可以帮他回答这个问题么？（序列的和为一个序列中所有数的总和。）</p>
</div> 

 
 # 输入格式 
<div class="colorize-content">
<p>第一行是一个整数N，表示序列的长度。</p>

<p>第二行是N个整数，分别表示A[1],A[2],...,A[N]。相邻数字由一个空格隔开。序列整数的绝对值不大于32767.</p>
</div> 

 
 # 输出格式 
<p>输出包括一行：最大的S(K)及其对应的K，用一个空格隔开，行尾使用回车符换行。若存在多个K其S(K)等于最大值，则输出较小的K。</p> 

 
 # 提示 
<div class="colorize-content">
<h2>样例说明</h2>

<p>S(1)=9,对应子序列为（4&nbsp;5）；S(2)=5，对应子序列为（1&nbsp;4）或（5）；S(3)=6，对应子序列为(1&nbsp;5);S(4)=5，对应子序列为（5）。</p>

<h2>数据范围</h2>

<p>对于所有的数据2&lt;=N&lt;=10000</p>

<h2>来源</h2>

<p>GDOI第二试第一题（广东2009）</p>

<h2>版权</h2>

<p>如有侵权，请告知！请管理员接到通知后请删题，O(&cap;_&cap;)O谢谢！</p>
</div> 
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
<tr><td>5
1 -5 4 5 -20</td><td>9 1</td></tr></table>
