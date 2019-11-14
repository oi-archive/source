# 

 
 # 题目描述 
<p>
　　在一个特殊的网络系统中有N台计算机，某个有关国家安全的信息需要在一个绝对安全的环境中从计算机1传递到计算机N。其中，我们规定以下安全策略：<br>　　A）每台计算机都与某些计算机相连，且为无向连通。<br>　　B）某计算机α需要安全验证，而这些验证必须由计算机β上取得，但计算机β并不一定和计算机α相连。<br>　　C）该信息必须在经过计算机β时即取得计算机α的安全验证，则之后可以进入计算机α，否则不能进入计算机α。 <br>　　D）信息只能在相邻的计算机之间传递，即使在取得β验证后也不能在α与β不相连的情况下直接到达α。<br>　　E）因为信息的重要程度，我们保证信息最终必能抵达计算机N。<br><br>　　由于网络传输需要时间，而每经过一台计算机消耗时间定为1，题目则要求求出传输该信息所需要的最短时间。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行为N(N≤80）。之后的第2到第N+1行分别描述计算机1到N，每行第一个数字为计算机i需要的安全验证的来源计算机编号j，在1到N 之间，若为0则无需验证。之后紧跟着的是与计算机i相连的计算机的编号，一直读到该行结束。</p> 

 
 # 输出格式 
<p>
　　输出文件仅一行，为传递所需要的最短时间。 </p> 

 
 # 提示 
<p>
<br><img src="/source/joyoi/tyvj-3140/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE0MC9wcm9ibGVtc19pbWFnZXMvMTQyNi8xLmJtcA==.bmp"></img>  </p> 
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
<tr><td></td><td></td></tr></table>
