# 

 
 # 题目背景 
今天是COCO的生日、、<BR>（PASSer&nbsp;A：我也知道、、）<BR>作为COCO的**，CH.Seb当然要做些什么、、 

 
 # 题目描述 
其次呢、、<BR>作为一次隆重的PARTY、<BR>一定是需要有地址的。（废话）<BR>但怎样是这个地址最方便呢？这就是你要解决的问题、。<BR><BR>COCO有很多朋友、、分布在N个城市。。<BR>这N个城市之间，有些有直接的道路，有些是间接联通的（保证任何两个城市都可以相互到达。。）<BR>但是、经过每条道路都是有代价的、、<BR>于是。。<BR>CH.Seb希望你来帮他找出一个城市，使得COCO的所有朋友到这个城市的代价最小、、、<BR><BR>现在呢、、Seb还有别的事情要忙。。<BR>SO，任务还是被交给了你来完成、、<BR>当然、、报酬照旧。。o(∩_∩)o&nbsp;、、 

 
 # 输入格式 
输入共2*n+1行，<BR>其中第一行为一个整数N、<BR>第2~N+1行<BR>每行有N个整数、表示两个城市间的代价、（0表示不直接连通）<BR>第n+2~2*N+1行<BR>每行一个整数。表示每个城市中COCO的朋友数、、 

 
 # 输出格式 
输出有两行、<BR>第一行为你选中的城市<BR>第二行为最小需要的代价。 

 
 # 提示 
对于30%的N，N&lt;=20;<BR>对于100%的N，&nbsp;1&lt;=N&lt;=200。<BR>By&nbsp;CH.Seb 
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
0 1 2 0 0 
1 0 0 0 20
2 0 0 10 0
0 0 10 0 1
0 20 0 1 0
2
3
4
5
6
</td><td>4
109
</td></tr></table>
