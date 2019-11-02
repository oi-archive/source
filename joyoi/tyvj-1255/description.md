# 

 
 # 题目背景 
NOI2010&nbsp;&nbsp;DAY1&nbsp;&nbsp;NO.1 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;栋栋有一块长方形的地，他在地上种了一种能量植物，这种植物可以采集太阳光的能量。在这些植物采集能量后，栋栋再使用一个能量汇集机器把这些植物采集到的能量汇集到一起。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;栋栋的植物种得非常整齐，一共有n列，每列有m棵，植物的横竖间距都一样，因此对于每一棵植物，栋栋可以用一个坐标(x,&nbsp;y)来表示，其中x的范围是1至n，表示是在第x列，y的范围是1至m，表示是在第x列的第y棵。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;由于能量汇集机器较大，不便移动，栋栋将它放在了一个角上，坐标正好是(0,&nbsp;0)。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;能量汇集机器在汇集的过程中有一定的能量损失。如果一棵植物与能量汇集机器连接而成的线段上有k棵植物，则能量的损失为2k&nbsp;+&nbsp;1。例如，当能量汇集机器收集坐标为(2,&nbsp;4)的植物时，由于连接线段上存在一棵植物(1,&nbsp;2)，会产生3的能量损失。注意，如果一棵植物与能量汇集机器连接的线段上没有植物，则能量损失为1。现在要计算总的能量损失。&nbsp;<BR>下面给出了一个能量采集的例子，其中n&nbsp;=&nbsp;5，m&nbsp;=&nbsp;4，一共有20棵植物，在每棵植物上标明了能量汇集机器收集它的能量时产生的能量损失。&nbsp;<BR><img src="/source/joyoi/tyvj-1255/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI1NS9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzEyNTUuanBn.jpg" border=0 align=middle><BR><BR>在这个例子中，总共产生了36的能量损失。<BR> 

 
 # 输入格式 
输入仅包含一行，为两个整数n和m。<BR> 

 
 # 输出格式 
输出仅包含一个整数，表示总共产生的能量损失。<BR> 

 
 # 提示 
对于10%的数据：1&nbsp;≤&nbsp;n,&nbsp;m&nbsp;≤&nbsp;10；<BR>对于50%的数据：1&nbsp;≤&nbsp;n,&nbsp;m&nbsp;≤&nbsp;100；<BR>对于80%的数据：1&nbsp;≤&nbsp;n,&nbsp;m&nbsp;≤&nbsp;1000；<BR>对于90%的数据：1&nbsp;≤&nbsp;n,&nbsp;m&nbsp;≤&nbsp;10,000；<BR>对于100%的数据：1&nbsp;≤&nbsp;n,&nbsp;m&nbsp;≤&nbsp;100,000。<BR> 
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
<tr><td>【样例输入1】
5 4
【样例输入2】
3 4

</td><td>【样例输出1】
36
【样例输出2】
20

</td></tr></table>
