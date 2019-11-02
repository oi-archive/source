# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;一个卡车司机在一条平坦的道路上行驶。这条路上有一些红绿灯，他不想在任何地方等红灯。由于他预先知道每个红绿灯的位置和周期，所以这个目的倒是很容易达到（大不了在路上开慢点，也不要在红绿灯处等待！）。不过如果考虑到油价的话这个任务就困难了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;开得太快是很费油的，开得太慢也是。更精确地，当行驶速度为v米/秒，则耗油速度为v+1/v-0.1毫升/秒。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第i个红绿灯离起点的位置为di，红灯周期为ri，绿灯周期为gi。即司机刚从起点出发时所有红绿灯刚刚开始它的红灯周期，经过ri秒后转到绿灯周期，再过gi后重新开始红灯周期…所有di各不相等，且都不在起点后终点。<BR>&nbsp;&nbsp;&nbsp;&nbsp;计算出保证不在红绿灯处等待的前提下从起点到终点所需要的最少油量。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件truck.in的第一行包括两个正整数D，L(D&lt;=10000,&nbsp;L&lt;=50)，即路<BR>程总长度和红绿灯的个数。以下L行每行三个正整数di，ri，gi，表示离起点的<BR>距离，红灯周期和绿灯周期。30&lt;=ri+gi&lt;=90。所有红绿灯按照离起点距离从小<BR>到大给出。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出文件truck.out仅包含一个数f，即最小耗油量，精确到小数点后两位。 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;本题不是数学题，只需要从数学的角度做一点初步分析。SCOI2004&nbsp;day1&nbsp;T4 
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
<tr><td>1000 3
250 20 20
500 40 40
750 19 19
</td><td>998.03
</td></tr></table>
