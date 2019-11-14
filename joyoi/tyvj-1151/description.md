# 

 
 # 题目描述 
土豆先生最近迷上了一种“旋转棋”，这种棋的下法是这样的：有一个大棋盘，这个大棋盘可以看作是一个平面直角坐标系。在棋盘上有一些兵，你需要在某一个位置放一个国王，使得国王的位置是所有兵的对称中心。<BR><BR>你的工作是使这个过程自动操作。给出一组N个点（兵的位置），你要找出它们的对称中心S，国王只能在这儿。下面以此类推。<BR><BR>首先我们给定一点A以及对称中心S，点A'是点A以S为对称中心形成的像点，即点S是线段AA'的对称中心。<BR><BR>点阵组{X}以S为中心的像点是由每个点的像点组成的点阵组。{X}是用来产生对称中心S的，即点阵X以S为中心的像点的集合即为点阵{X}本身。 

 
 # 输入格式 
输入文件第一行是一个整数N，1&lt;=N&lt;=20000。接下来的N行包含用空格隔开的两个整数Xi和Yi，-100000&lt;=Xi,Yi&lt;=100000，表示第I个兵的坐标。任意两个兵不可能在同样的位置，但国王可以站在兵的位置上。 

 
 # 输出格式 
输出文件有一行。如果你可以放国王，则输出"You&nbsp;put&nbsp;the&nbsp;king&nbsp;at&nbsp;(x,y)."，X和Y表示国王的坐标，要四舍五入至小数点后一位。如果不可以放国王，则输出"You&nbsp;can&nbsp;not&nbsp;put&nbsp;the&nbsp;king!"。 
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
<tr><td>8
1 10
3 6
6 8
6 2
3 -4
1 0
-2 -2
-2 4
</td><td>You put the king at (2.0,3.0).
</td></tr></table>
