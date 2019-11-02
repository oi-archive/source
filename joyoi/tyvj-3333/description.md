# 

 
 # 题目描述 
<p>
网络监控器（netwatch.pas/c/cpp）<br><br>【问题描述】<br>　　为了保证网络通信的可靠性，我们需要监控每台服务器的运作情况以保证其能正常地工作。为此，GDOI网络设备公司新近推出了一种名为网络监控器（型号GDOI-007）的设备。将网络监控器安装在某通顺服务器上后，所有跟些服务器直接相连的服务器都能得到监控。为了节省开支，我们希望能用最少的网络监控器去监控一个通信网络中心的所有服务器。你现在的任务即是如此。<br></p> 

 
 # 输入格式 
<p>
　　输入文件netwatch.in第一行是一个正整数N，为通信网络中服务器的台数。接下来的若干行数据描述了网络的构成。每一行的格式如下：<br>　　A　C1　C2　…　Cd(A)  0<br>　　表示编号为C1、C2、…、Cd(A)的服务器与编号为A的服务器直接相连（d(A)是与服务器A直接相连的服务器总数）。行末以数字0结束。<br>　　各数之间用一个空格隔开，输入文件以－1结束。<br></p> 

 
 # 输出格式 
<p>
　　输出文件netwatch.out只有一行，即需要安装网络监控器的服务器编号列表。编号以升序排列，之间用一个空格隔开，行末以数字0结束。</p> 
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
<tr><td>7
1　2　4　0
2　3　4　0
3　4　0
4　5　6　7　0
5　6　0
6　7　0
－1
</td><td>4　0</td></tr></table>
