# 

 
 # 题目描述 
小华最近迷上了一个你小时候已经玩厌了的游戏：移火柴棒。他现在吵着要你陪他玩，你没有办法，只好写一个程序来完成这个工作了。<BR>你被给出了一个火柴拼成的等式，比如说下面这个：（&nbsp;5&nbsp;+&nbsp;7&nbsp;=&nbsp;7&nbsp;）<BR><img src="/source/joyoi/tyvj-1603/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTYwMy9odHRwOi8vYmJzLnBhaXBhaS5jb20vZGF0YS9hdHRhY2htZW50L2ZvcnVtLzIwMTEwOC8yMi8xMDEyNTk5OXJndnYwaGk5OWJmOTkxLmdpZg==.gif" border=0 align=middle><BR>它显然是不成立的，但是我们可以通过移动一个其中的火柴使得它成立。变成如下的一个等式：(&nbsp;6&nbsp;+&nbsp;1&nbsp;=&nbsp;7&nbsp;)<BR><img src="/source/joyoi/tyvj-1603/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTYwMy9odHRwOi8vYmJzLnBhaXBhaS5jb20vZGF0YS9hdHRhY2htZW50L2ZvcnVtLzIwMTEwOC8yMi8xMDEyNTlocXFuMTc3eWdjdW91ZGdlLmdpZg==.gif" border=0 align=middle><BR>现在给出一个类似的等式，请问最少移动多少根火柴可以使得它变成一个成立的等式。<BR>每个数字的表示方法如下：我们用7根火柴表示每一个数字。火柴编号0~6，如下图所示：<BR><img src="/source/joyoi/tyvj-1603/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTYwMy9odHRwOi8vYmJzLnBhaXBhaS5jb20vZGF0YS9hdHRhY2htZW50L2ZvcnVtLzIwMTEwOC8yMi8xMDEzMDBya2tvMHFoMDBoamowcmV1LmdpZg==.gif" border=0 align=middle><BR>每一个数字都可以用对应的火柴组成的集合表示：<BR>1&nbsp;~&nbsp;{2,&nbsp;5}&nbsp;or&nbsp;{1,&nbsp;4}<BR>2~&nbsp;{0,&nbsp;2,&nbsp;3,&nbsp;4,&nbsp;6}<BR>3&nbsp;~&nbsp;{0,&nbsp;2,&nbsp;3,&nbsp;5,&nbsp;6}<BR>4&nbsp;~&nbsp;{1,&nbsp;2,&nbsp;3,&nbsp;5}<BR>5&nbsp;~&nbsp;{0,&nbsp;1,&nbsp;3,&nbsp;5,&nbsp;6}<BR>6&nbsp;~&nbsp;{0,&nbsp;1,&nbsp;3,&nbsp;4,&nbsp;5,&nbsp;6}<BR>7&nbsp;~&nbsp;{0,&nbsp;2,&nbsp;5}<BR>8&nbsp;~&nbsp;{0,&nbsp;1,&nbsp;2,&nbsp;3,&nbsp;4,&nbsp;5,&nbsp;6}<BR>9&nbsp;~&nbsp;{0,&nbsp;1,&nbsp;2,&nbsp;3,&nbsp;5,&nbsp;6}<BR>0&nbsp;~&nbsp;{0,&nbsp;1,&nbsp;2,&nbsp;4,&nbsp;5,&nbsp;6} 

 
 # 输入格式 
输入有三个数，分别表示上面的表达式中的三个数。每个数都在0~999之间 

 
 # 输出格式 
输出只需要一个数，表示使等式成立最少需要移动的火柴数，不允许改变位数以及符号，不要制造0开头的数。 
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
<tr><td>5 7 7
</td><td>1
</td></tr></table>
