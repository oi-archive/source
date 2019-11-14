# 

 
 # 题目描述 
<p>
追捕工作（pursuit.pas\c\cpp） <br><br>【题目描述】 <br>　　TOM猫又在想新办法抓JERRY鼠。这次，TOM想到了用机关来捕抓JERRY。于是它便动工做了一个追捕机关。<br>　　该机关可以看成是一幅有向图。有多个汇点（该点不再连出其它边），和多个原点（该点不被其它任何边指住），而这幅图的的每一点便是一个机关。要启动一个机关，必须要连向该机关的其它所有机关均已启动。而机关启动后，需要一定的时间去激活它所连接的机关。例如：如果有机关A－>B，其传递时间为5。即启动机关A后，5个单位时间后B才能被启动；A－>B，传递时间为5，C—>B，传递时间为9。A激活B用了5个单位时间，而C激活B用了9个单位时间，所以B被启动时，是用了9的单位时间。边表示的是这个传递时间。<br>　　明显，这个机关是不足以抓住JERRY鼠的。因为启动机关就花费了太多的时间。所以TOM想知道，究竟这个机关完全启动时究竟耗了多少时间（即，所有机关都启动了）。<br></p> 

 
 # 输入格式 
<p>
　　输入文件pursuit.in：<br>　　N M(N表示有N个点，M表示有M条边)<br>　　有M行的X Y W（表示X要激活Y所需时间为W）<br>　　1<=N<=100,1<=M<=5050<br>　　1<=X,Y<=N,1<=W<=100<br></p> 

 
 # 输出格式 
<p>
　　输出文件pursuit.out包含启动最后一个机关的用时。如果无法启动，则输出-1。</p> 
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
<tr><td>5 4
1 2 3
2 3 5
3 5 6
4 5 3
</td><td>14</td></tr></table>
