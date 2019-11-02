# 

 
 # 题目背景 
<p>Rainbow和Freda终于走出了幻象迷宫，不过经历了汪星人的一场入侵，Freda的城堡和Rainbow的城堡之间的电话线路出了故障，使得只有满足某种要求的两个电话号码之间才可以直接通信。</p> 

 
 # 题目描述 
<p>每台电话都有一个独一无二的号码，用一个十位的十进制数字串表示。电话a和b之间能直接通信，当且仅当&ldquo;a与b之间仅有一个数字不同&rdquo;，或者&ldquo;交换a的某两位上的数字后，a与b相同&rdquo;。而a、b之间建立通信联系所需要的时间为cost[&nbsp;lcp(a,b)&nbsp;]，其中cost[]是一个常数数组，lcp(a,b)表示a、b的最长公共前缀的长度，lcp(a,b)越大，通信时间越快。<br />
另外，如果a、b能通信，b、c能通信，那么a、c也能借助b来通信。a、c借助b建立通信联系所用时间是cost[&nbsp;lcp(a,b)&nbsp;]+&nbsp;cost[&nbsp;lcp(b,c)&nbsp;]。<br />
现在Freda想给Rainbow打电话，请你告诉Freda，她最快需要多少时间才能与与Rainbow建立通信联系？</p> 

 
 # 输入格式 
<p>第一行一个整数N，表示电话号码的个数。<br />
第二行10个整数，第i个整数表示cost[i-1]，即当两个能够直接通信的号码的最长公共前缀为i-1时，二者之间建立通信联系所需的时间。<br />
接下来N行每行一个整数表示电话号码。第一个是Freda的电话号码，第N个是Rainbow的电话号码。</p> 

 
 # 输出格式 
<p>一个整数，表示所求时间。若Freda和Rainbow不能建立通信联系，输出-1。</p> 

 
 # 提示 
<p>对于&nbsp;30%&nbsp;的数据，2&lt;=N&lt;=100。<br />
对于&nbsp;50%&nbsp;的数据，2&lt;=N&lt;=1000。<br />
对于&nbsp;70%&nbsp;的数据，2&lt;=N&lt;=20000。<br />
对于&nbsp;100%&nbsp;的数据，保证2&lt;=N&lt;=50000，每个电话号码是一个独一无二的十位十进制数字串，1&lt;=cost[0..9]&lt;=2^31-1。</p> 
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
100 10 10 10 1 1 1 1 1 1
9123493342
3123493942
9223433942
3223493942
9223433945
</td><td>211
</td></tr></table>
