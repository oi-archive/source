# 

 
 # 题目背景 
USACO&nbsp;OCT09&nbsp;4TH 

 
 # 题目描述 
Bessie不小心游荡出Farmer&nbsp;John的田地，而走进了相邻的农民的地。她举起一个木瓜，木<BR>瓜对奶牛来说可是不可多得得美味。这个木瓜林像一般的威斯康星州的田地一样被分割成一个<BR>R行C列的网格(1&nbsp;&lt;=&nbsp;R&nbsp;&lt;=&nbsp;40,&nbsp;1&nbsp;&lt;=&nbsp;C&nbsp;&lt;=&nbsp;40)。Bessie可以从一个格沿著一条跟X轴或<BR>Y轴平行的直线走到邻接的令一个格。Bessie发现一开始她自己在木瓜林的(1,1)，也就是第<BR>一行第一列慢悠悠地咀嚼著木瓜。<BR><BR>Bessie总是用她最信赖地双筒望远镜去数每一个邻接的格的低掛著的木瓜的数目。然后她就游<BR>荡到那个有最多没有被吃掉的木瓜的邻接的格子（保证这洋的格子只有一个）。<BR><BR>按照这种移动方法，最终Bessie总是会在(R,C)停止然后吃掉那裡的木瓜。<BR><BR>给定这个木瓜林的大小及每个格的木瓜数F_ij(1&nbsp;&lt;=&nbsp;F_ij&nbsp;&lt;=&nbsp;100),&nbsp;要求Bessie一共吃了<BR>多少个木瓜。 

 
 # 输入格式 
*&nbsp;第一行:&nbsp;两个空格隔开的整数R和C.<BR><BR>*&nbsp;第2到R+1行:&nbsp;第i+1行有C个空格隔开的整数，表示第i行的每个格的水果数。也就是F_i1,&nbsp;<BR>	F_i2,&nbsp;...,&nbsp;F_iC. 

 
 # 输出格式 
*&nbsp;第一行:&nbsp;一个单独的整数，表示到Bessie吃完右下角(R,C)的木瓜回到牛棚的时候為止，<BR>	一共在木瓜林吃掉了多少个木瓜。 

 
 # 提示 
Bessie按照下图数字旁边的字母的顺序吃掉木瓜。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1,1)&nbsp;---&gt;&nbsp;(1,C)<BR>(1,1)&nbsp;3a&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;4g&nbsp;&nbsp;5h&nbsp;&nbsp;(1,C)<BR>&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;4b&nbsp;&nbsp;5c&nbsp;&nbsp;3f&nbsp;&nbsp;2i&nbsp;&nbsp;&nbsp;&nbsp;|<BR>(R,1)&nbsp;1&nbsp;&nbsp;&nbsp;7d&nbsp;&nbsp;4e&nbsp;&nbsp;2j&nbsp;&nbsp;(R,C)<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(R,1)&nbsp;---&gt;&nbsp;(R,C)<BR><BR>她吃了39个木瓜，剩下4个没有吃（也就是说除了2个格幸免於难，剩下的格子都被Bessie扫<BR>荡过了）。<BR><BR> 
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
<tr><td>3 4
3 3 4 5
4 5 3 2
1 7 4 2</td><td>39</td></tr></table>
