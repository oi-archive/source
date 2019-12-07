# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在&nbsp;caima&nbsp;的&nbsp;RPG&nbsp;游戏中，控制着两个人&nbsp;VV&nbsp;和&nbsp;JJ。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这次&nbsp;VV&nbsp;和&nbsp;JJ&nbsp;掉入了一个死亡洞穴，洞穴是一个&nbsp;N*M&nbsp;的矩阵。之所以称之<BR>为死亡洞穴，是因为在这个矩阵中有一些死亡十字。(如下图中的+)<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.....<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.+++.<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.+.+.<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;V+.J+<BR>&nbsp;&nbsp;&nbsp;&nbsp;由于&nbsp;VV&nbsp;和&nbsp;JJ&nbsp;被分撒在了两地，而&nbsp;JJ&nbsp;还受了重伤，你需要让&nbsp;VV&nbsp;赶到&nbsp;JJ&nbsp;所<BR>在的地方。为了尽量少的受死亡十字的影响，VV&nbsp;要尽量远离这些死亡十字。<BR>&nbsp;&nbsp;&nbsp;&nbsp;我们定义洞穴中两个格子(x,y)和(x’,y’)之间的距离为：|x-x'|&nbsp;+&nbsp;|y-y'|<BR>&nbsp;&nbsp;&nbsp;&nbsp;也就是说，我们要使得&nbsp;VV&nbsp;再去找&nbsp;JJ&nbsp;的路上，离任意死亡十字的距离都尽<BR>可能的远。VV&nbsp;每次可以往一个格子的上下左右四个方向走一格。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在你需要写个程序，来计算最好情况下离死亡十字最近的距离。<BR> 

 
 # 输入格式 
第一行两个整数&nbsp;N&nbsp;和&nbsp;M，表示矩阵规模。<BR>接下来&nbsp;N&nbsp;行&nbsp;M&nbsp;列，描述这个洞穴的情况。其中<BR>V&nbsp;表示&nbsp;VV&nbsp;所在的位置；<BR>J&nbsp;表示&nbsp;JJ&nbsp;所在的位置；<BR>.&nbsp;表示空地；<BR>+&nbsp;表示死亡十字。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一行一个数字，表示&nbsp;VV&nbsp;在去找&nbsp;JJ&nbsp;的路上，最好情况下离死亡十字最近的距离。<BR> 

 
 # 提示 
数据规模<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于&nbsp;30%&nbsp;的数据&nbsp;N,M&lt;=50。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于&nbsp;100%&nbsp;的数据&nbsp;N,M&lt;=500。<BR>清北学堂模拟赛，第二场，第四题。 
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
<tr><td>4 4
+...
....
....
V..J
</td><td>3</td></tr></table>
