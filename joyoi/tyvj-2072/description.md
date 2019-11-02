# 

 
 # 题目背景 
NOIP&nbsp;2012&nbsp;提高组&nbsp;题2 

 
 # 题目描述 
恰逢&nbsp;H&nbsp;国国庆,国王邀请&nbsp;n&nbsp;位大臣来玩一个有奖游戏。首先,他让每个大臣在左、右手上面分别写下一个整数,国王自己也在左、右手上各写一个整数。然后,让这&nbsp;n&nbsp;位大臣排成一排,国王站在队伍的最前面。排好队后,所有的大臣都会获得国王奖赏的若干金币,每位大臣获得的金币数分别是:排在该大臣前面的所有人的左手上的数的乘积除以他自己右手上的数,然后向下取整得到的结果。<br>国王不希望某一个大臣获得特别多的奖赏,所以他想请你帮他重新安排一下队伍的顺序,使得获得奖赏最多的大臣,所获奖赏尽可能的少。注意,国王的位置始终在队伍的最前面。 

 
 # 输入格式 
第一行包含一个整数&nbsp;n,表示大臣的人数。<br>第二行包含两个整数&nbsp;a&nbsp;和&nbsp;b,之间用一个空格隔开,分别表示国王左手和右手上的整数。<br>接下来&nbsp;n&nbsp;行,每行包含两个整数&nbsp;a&nbsp;和&nbsp;b,之间用一个空格隔开,分别表示每个大臣左手和右手上的整数。 

 
 # 输出格式 
输出只有一行,包含一个整数,表示重新排列后的队伍中获奖赏最多的大臣所获得的金币数。<br> 

 
 # 提示 
【输入输出样例说明】<br>按&nbsp;1、2、3&nbsp;号大臣这样排列队伍,获得奖赏最多的大臣所获得金币数为&nbsp;2;<br>按&nbsp;1、3、2&nbsp;这样排列队伍,获得奖赏最多的大臣所获得金币数为&nbsp;2;<br>按&nbsp;2、1、3&nbsp;这样排列队伍,获得奖赏最多的大臣所获得金币数为&nbsp;2;<br>按&nbsp;2、3、1&nbsp;这样排列队伍,获得奖赏最多的大臣所获得金币数为&nbsp;9;<br>按&nbsp;3、1、2&nbsp;这样排列队伍,获得奖赏最多的大臣所获得金币数为&nbsp;2;<br>按&nbsp;3、2、1&nbsp;这样排列队伍,获得奖赏最多的大臣所获得金币数为&nbsp;9。<br>因此,奖赏最多的大臣最少获得&nbsp;2&nbsp;个金币,答案输出&nbsp;2。<br>【数据范围】<br>对于&nbsp;20%的数据,有&nbsp;1≤&nbsp;n≤&nbsp;10,0&nbsp;&lt;&nbsp;a、b&nbsp;&lt;&nbsp;8;<br>对于&nbsp;40%的数据,有&nbsp;1≤&nbsp;n≤20,0&nbsp;&lt;&nbsp;a、b&nbsp;&lt;&nbsp;8;<br>对于&nbsp;60%的数据,有&nbsp;1≤&nbsp;n≤100;<br>对于&nbsp;60%的数据,保证答案不超过&nbsp;109;<br>对于&nbsp;100%的数据,有&nbsp;1&nbsp;≤&nbsp;n&nbsp;≤1,000,0&nbsp;&lt;&nbsp;a、b&nbsp;&lt;&nbsp;10000。NOIP&nbsp;2012 
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
<tr><td>3
1 1
2 3
7 4
4 6</td><td>2</td></tr></table>
