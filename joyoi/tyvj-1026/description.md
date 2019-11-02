# 

 
 # 题目背景 
USACO&nbsp;OCT&nbsp;09&nbsp;2ND 

 
 # 题目描述 
Farmer&nbsp;John為了让自己从无穷无尽的犁田工作中解放出来，於是买了个新机器人帮助他犁田。这个机器人可以完成犁田的任务，可惜有一个小小的缺点：这个犁田机器人一次只能犁一个边的长度是整数的长方形的田地。<BR><BR>因為FJ的田地有树和其他障碍物，所以FJ设定机器人去犁很多不同的长方形。这些长方形允许重叠。他给机器人下了P个指令，每个指令包含一个要犁长方形的地。这片田地由长方形的左下角和右上角坐标决定。他很好奇最后到底有多少个方格的地被犁过了。<BR><BR>一般来说，田地被分割為很多小方格。这些方格的边和x轴或y轴平行。田地的宽度為X个方格，高度為Y个方格&nbsp;(1&nbsp;&lt;=&nbsp;X&nbsp;&lt;=&nbsp;240;&nbsp;1&nbsp;&lt;=&nbsp;Y&nbsp;&lt;=&nbsp;240).&nbsp;FJ执行了I&nbsp;(1&nbsp;&lt;=&nbsp;I&nbsp;&lt;=&nbsp;200)个指令，每个指令包含4个整数：Xll,&nbsp;Yll,&nbsp;Xur,&nbsp;Yur&nbsp;(1&nbsp;&lt;=&nbsp;Xll&nbsp;&lt;=Xur;&nbsp;Xll&nbsp;&lt;=&nbsp;Xur&nbsp;&lt;=X;&nbsp;1&nbsp;&lt;=&nbsp;Yll&nbsp;&lt;=&nbsp;Yur;&nbsp;Yll&nbsp;&lt;=&nbsp;Yur&nbsp;&lt;=&nbsp;Y),&nbsp;分别是要犁的长方形的左下角坐标和右上角坐标。机器人会犁所有的横坐标在Xll..Xur并且纵坐标Yll..Yur范围内的所有方格的地。可能这个长方形会比你想像的多一行一列（就是说从第Xll列到第Xur列一共有Xur&nbsp;-&nbsp;Xll&nbsp;+&nbsp;1列而不是Xur&nbsp;-&nbsp;Xll列）。<BR><BR>考虑一个6方格宽4方格高的田地。FJ进行了2个操作（如下），田地就被成"*"和"#"了。虽然一般被犁过的地看起来都是一样的。但是标成"#"可以更清晰地看出最近一次被犁的长方形。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;......&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**....&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#####.<BR>&nbsp;&nbsp;&nbsp;&nbsp;......&nbsp;&nbsp;(1,1)(2,4)&nbsp;**....&nbsp;&nbsp;(1,3)(5,4)&nbsp;#####.<BR>&nbsp;&nbsp;&nbsp;&nbsp;......&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**....&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**....<BR>&nbsp;&nbsp;&nbsp;&nbsp;......&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**....&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**....<BR><BR>一共14个方格的地被犁过了。<BR> 

 
 # 输入格式 
*&nbsp;第一行:&nbsp;三个由空格隔开的整数：&nbsp;X,&nbsp;Y,&nbsp;I<BR><BR>*&nbsp;第二行到第I+1行：第i+1行有四个整数Xll,&nbsp;Yll,&nbsp;Xur,&nbsp;Yur，表示第i个指令。<BR> 

 
 # 输出格式 
第一行:&nbsp;一个单独的整数表示被犁过的方格数。<BR> 
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
<tr><td>6 4 2
1 1 2 4
1 3 5 4
</td><td>14
</td></tr></table>
