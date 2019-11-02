# 

 
 # 题目背景 
SuperBrother在机房里闲着没事干(再对比一下他的NOIP,真是讽刺啊......),于是便无聊地开始玩“打鼹鼠”...... 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在这个“打鼹鼠”的游戏中，鼹鼠会不时地从洞中钻出来，不过不会从洞口钻进去（鼹鼠真胆大……）。洞口都在一个大小为n(n&lt;=1024)的正方形中。这个正方形在一个平面直角坐标系中，左下角为(0,0)，右上角为(n-1,n-1)。洞口所在的位置都是整点，就是横纵坐标都为整数的点。而SuperBrother也不时地会想知道某一个范围的鼹鼠总数。这就是你的任务。 

 
 # 输入格式 
每个输入文件有多行。<BR>第一行，一个数n，表示鼹鼠的范围。<BR>以后每一行开头都有一个数m，表示不同的操作：<BR>m=1，那么后面跟着3个数x,y,k(0&lt;=x,y&lt;n)，表示在点(x,y)处新出现了k只鼹鼠；<BR>m=2，那么后面跟着4个数x1,y1,x2,y2(0&lt;=x1&lt;=x2&lt;n,0&lt;=y1&lt;=y2&lt;n)，表示询问矩形(x1,y1)-(x2,y2)内的鼹鼠数量；<BR>m=3，表示老师来了，不能玩了。保证这个数会在输入的最后一行。<BR>询问数不会超过10000，鼹鼠数不会超过maxlongint。 

 
 # 输出格式 
对于每个m=2，输出一行数，这行数只有一个数，即所询问的区域内鼹鼠的个数。 

 
 # 提示 
水题一道。<BR>所有数据均为随机生成，包括样例……gnaggnoyil 
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
<tr><td>4
1 2 2 5
2 0 0 2 3
3
</td><td>5
</td></tr></table>
