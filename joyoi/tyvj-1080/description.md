# 

 
 # 题目描述 
检查一个如下的6&nbsp;x&nbsp;6的跳棋棋盘，有六个棋子被放置在棋盘上，使得每行、每列只有一个，每条对角线(包括两条主对角线的所有平行线)上至多有一个棋子。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;列号<BR>　　&nbsp;1　&nbsp;2　&nbsp;3　&nbsp;4　&nbsp;5　&nbsp;6&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>1&nbsp;|　&nbsp;|&nbsp;O&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>2&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|&nbsp;O&nbsp;|　&nbsp;|　&nbsp;|&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>3&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|&nbsp;O&nbsp;|&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>4&nbsp;|&nbsp;O&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>5&nbsp;|　&nbsp;|　&nbsp;|&nbsp;O&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>6&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|　&nbsp;|&nbsp;O&nbsp;|　&nbsp;|&nbsp;<BR><BR>　　-------------------------&nbsp;<BR><BR>上面的布局可以用序列2&nbsp;4&nbsp;6&nbsp;1&nbsp;3&nbsp;5来描述，第i个数字表示在第i行的相应位置有一个棋子，如下：&nbsp;<BR>行号&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6&nbsp;<BR>列号&nbsp;2&nbsp;4&nbsp;6&nbsp;1&nbsp;3&nbsp;5&nbsp;<BR>这只是跳棋放置的一个解。请编一个程序找出所有跳棋放置的解。并把它们以上面的序列方法输出。解按字典顺序排列。请输出前3个解。最后一行是解的总个数。&nbsp;<BR>特别注意:&nbsp;对于更大的N(棋盘大小N&nbsp;x&nbsp;N)你的程序应当改进得更有效。不要事先计算出所有解然后只输出(或是找到一个关于它的公式），这是作弊。如果你坚持作弊，那么你登陆tyvj的帐号将被无警告删除&nbsp;<BR> 

 
 # 输入格式 
一个数字N&nbsp;(6&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;13)&nbsp;表示棋盘是N&nbsp;x&nbsp;N大小的。&nbsp;<BR><BR> 

 
 # 输出格式 
前三行为前三个解，每个解的两个数字之间用一个空格隔开。第四行只有一个数字，表示解的总数。&nbsp;<BR><BR> 

 
 # 提示 
usaco 
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
<tr><td>6</td><td>2 4 6 1 3 5 
3 6 2 5 1 4 
4 1 5 2 6 3 
4
</td></tr></table>
