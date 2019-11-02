# 

 
 # 题目描述 
<p>
一个XOR门包含两个输入和一个输出，它的工作可以用下表描述：<br><br><center><img src="/source/joyoi/tyvj-2794/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc5NC9wcm9ibGVtc19pbWFnZXMvMzMxNy9wZy5qcGc=.jpg"></img></center><br>如果一个XOR门系统有n个输入和1个输出，且满足以下条件，则称这个XOR门系统为XOR网络。<br>1.	系统的每一个输入都至少与一个XOR门的输入端相连；<br>2.	系统中每个门的输入必须与系统的一个输入或另一个门的输出连接；<br>3.	有且只有有一个门的输出与系统的输出相连；<br>4.	每个门的输出要与另外至少一个门的输入或系统的输出相连；<br>5.	这些XOR门存在一种编号方式，使得每个门的输入都与系统的输入或具有较小编号的门的输出相连。<br><br>图中有一个由6个XOR门组成的XOR系统。它有5个输入和1个输出，它满足以上的5个条件，所以它是一个XOR网络。注意：图中给出的编号方式不满足条件5，但可以找到一种满足条件的编号方式。<br>网络的输入标号为1到5，一种输入状态可以用一个长度为n的字符串表示，每一位是0或1，我们假设第I个数字表示第I个输入的状态。每一个输入都是一个自然数的二进制编码，所以我们可以按输入状态表示的数值的大小将它们排序。我们要测试一个电路门网络，通过向它发送一个范围以内的输入，计算使输出是1的输入个数。<br><br><center><img src="/source/joyoi/tyvj-2794/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc5NC9wcm9ibGVtc19pbWFnZXMvMzMxNy9wZzIuanBn.jpg"></img></center><br>计算给定范围内有多少种输入可以使输出为1。<br>我们假设3 < n < 100, 3 < m < 3000，而且网络中的门是用1到m之间的数任意编号的。<br><br></p> 

 
 # 输入格式 
<p>
文件第一行包含三个整数，分别表示输入的个数，门的个数，连接到输出的门的编号。以下的m行描述网络中的连接情况。第I行表示第I个门的两个输入，两个输入为范围[-n,m]之间的一个整数。如果输入是网络的第k个输入，则连接的描述是一个整数－k，如果输入是第j个门，则连接的描述是一个整数j。以下两行各有一个n位二进制串，表示输入的上限和下限。</p> 

 
 # 输出格式 
<p>
输出文件包含一个整数，表示给定范围内有多少种输入可以使输出为1。</p> 
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
<tr><td>5 6 5
-1 -2
1 3
1 -2
2 -3
4 6
-4 -5
00111
01110
</td><td>5</td></tr></table>
