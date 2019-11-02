# 

 
 # 题目描述 
<p>
聪明的质监员(qc.cpp/c/pas)<br><br>【问题描述】<br><br>　　小 T 是一名质量监督员，最近负责检验一批矿产的质量。这批矿产共有n 个矿石，从1到n 逐一编号，每个矿石都有自己的重量wi 以及价值vi。检验矿产的流程是：<br>　　1、给定m 个区间[Li，Ri]；<br>　　2、选出一个参数W；<br>　　3、对于一个区间[Li，Ri]，计算矿石在这个区间上的检验值Yi ：<br><br><center><img src="/source/joyoi/tyvj-3112/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzExMi9wcm9ibGVtc19pbWFnZXMvMTM1OC9wMS5naWY=.gif"></img></center><br><br>　　若这批矿产的检验结果与所给标准值S 相差太多，就需要再去检验另一批矿产。小T不想费时间去检验另一批矿产，所以他想通过调整参数W 的值，让检验结果尽可能的靠近标准值S，即使得S-Y 的绝对值最小。请你帮忙求出这个最小值。</p> 

 
 # 输入格式 
<p>
输入文件 qc.in。<br>　　第一行包含三个整数 n，m，S，分别表示矿石的个数、区间的个数和标准值。<br>　　接下来的 n 行，每行2 个整数，中间用空格隔开，第i+1 行表示i 号矿石的重量wi 和价值vi 。<br>　　接下来的 m 行，表示区间，每行2 个整数，中间用空格隔开，第i+n+1 行表示区间[Li,Ri]的两个端点Li 和Ri。注意：不同区间可能重合或相互重叠。</p> 

 
 # 输出格式 
<p>
输出文件名为 qc.out。<br>　　输出只有一行，包含一个整数，表示所求的最小值。</p> 

 
 # 提示 
<p>
【输入输出样例说明】<br>　　当 W 选4 的时候，三个区间上检验值分别为20、5、0，这批矿产的检验结果为25，此时与标准值S 相差最小为10。<br><br>【数据范围】<br>对于 10%的数据，有1≤n，m≤10；<br>对于 30%的数据，有1≤n，m≤500；<br>对于 50%的数据，有1≤n，m≤5,000；<br>对于 70%的数据，有1≤n，m≤10,000；<br>对于 100%的数据，有1≤n，m≤200,000，0 < wi, vi≤106，0 < S≤1012，1≤Li≤Ri≤n。</p> 
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
<tr><td>5 3 15
1 5
2 5
3 5
4 5
5 5
1 5
2 4
3 3</td><td>10</td></tr></table>
