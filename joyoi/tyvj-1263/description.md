# 

 
 # 题目背景 
蛟川书院模拟试题 

 
 # 题目描述 
TOM要搬家了，大家都来帮忙。<BR>TOM现在住在第N楼，总共K个人要把X个大箱子搬上N楼。<BR>最开始X个箱子都在1楼，但是经过一段混乱的搬运已经乱掉了。最后大家发现这样混乱的搬运过程效率太低了，于是总结出了提高效率的办法。<BR>大家的速度都是用一分钟上（或者下）一层楼。所有向上走的人手中拿一个箱子，所有向下走的人手中都不拿箱子。到达第N层立刻放下箱子向下走，到达第1层立刻拿起箱子向上走。当一个人向上走，另一个人向下走而在楼道里相遇时，向上走的人将手中的&nbsp;箱子交给另一个人，两人同时反向。即原来拿箱子向上走的人不拿箱子向下走，原来不拿箱子的向下走的人先拿着箱子想上走。<BR>求将所有箱子搬完所需要的最短时间。<BR> 

 
 # 输入格式 
第一行N（N&lt;=10^9）,k(k&lt;=500000)，M（M&lt;=10^9），分别表示楼层数、人数、还放在一楼地上的箱子数。<BR>接下来K行，每行两个数Ai,Bi。<BR>Ai表示第i人现所在的楼层数，Bi为0或者1，为0表示第i人正拿着箱子向上走，为1表示第i人不拿箱子向下走。<BR>输入满足没有任意两人正在同一楼层，在第1层的人一定正拿着箱子向上走，在第N层的人一定正不拿箱子向下走。<BR> 

 
 # 输出格式 
仅包含一个整数，为搬完箱子的时间。 

 
 # 提示 
对于30%的数据有k&lt;=100,M&lt;=100;<BR>对于60%的数据有k&lt;=1000,M&lt;=10^9<BR>对于100%的数据有k&lt;=500000,M&lt;=10^9<BR>Moe-ing 
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
<tr><td>5 2 4
1 0
3 0
</td><td>20</td></tr></table>
