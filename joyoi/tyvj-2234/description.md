# 

 
 # 题目描述 
<p>
巴多兰克斯经的游戏<br>　　国际象棋的棋盘是8*8的。一个骑士可以攻击到8个位置（和中国象棋的马的走法类似，此不赘述）。<br>　　在一个古老的游戏中，游戏者可以把一个骑士放在棋盘上，骑士就控制了它所在的位置。同时，骄傲的骑士可以从它可攻击的8个位置中，选择一个，作为它的控制领域。也就是说，一个骑士最多可以事实上控制棋盘中的两个格子。游戏允许游戏者任意放置骑士，并且任意安排这些骑士所控制的格子。最后的目的是要用最少的骑士控制棋盘上的每一个格子。<br>　　小修在《巴多兰克斯经》上发现了这个古老的游戏，她哈哈大笑，很快就完成了这个简单的游戏。<br>　　这时候天凯来串门了，他看了看这个游戏说：“太弱智了。干脆改成n*n的棋盘吧！”他想了想还不满意，又说：“另外还要把某些格子挖掉！”当然，这些挖掉的格子既不能放骑士，也不需要任何骑士去控制它。这么一改，可把小修难住了。聪明的你能解决这个问题吗？<br><br></p> 

 
 # 输入格式 
<p>
　　第一行n(n <= 20)<br>　　以下若干行每行两个数a, b，表示第a行第b列的格子被挖掉了。<br></p> 

 
 # 输出格式 
<p>
　　仅一个整数，即最少放置的骑士数。<br></p> 

 
 # 提示 
<p>
说明：放置方法如下<br><br><br><center><img src="/source/joyoi/tyvj-2234/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjIzNC9wcm9ibGVtc19pbWFnZXMvMTA5NC8xLmJtcA==.bmp"></img></center>　</p> 
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
<tr><td>Knight.in
3
2 2

</td><td>Knight.out
4
</td></tr></table>
