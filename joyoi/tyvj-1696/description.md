# 

 
 # 题目背景 
NOIP2011&nbsp;day2&nbsp;第二题<BR> 

 
 # 题目描述 
小T&nbsp;是一名质量监督员，最近负责检验一批矿产的质量。这批矿产共有&nbsp;n&nbsp;个矿石，从&nbsp;1到n&nbsp;逐一编号，每个矿石都有自己的重量&nbsp;wi&nbsp;以及价值vi&nbsp;。检验矿产的流程是：&nbsp;<BR>1&nbsp;、给定m&nbsp;个区间[Li&nbsp;，Ri]；&nbsp;<BR>2&nbsp;、选出一个参数&nbsp;W；&nbsp;<BR>3&nbsp;、对于一个区间[Li&nbsp;，Ri],计算矿石在这个区间上的检验值Yi:<BR>	Yi=Σ1*Σvj，Σ的循环变量为j，这里j要满足j∈[Li,Ri]且wj≥W，这里j是矿石编号。<BR><BR>这批矿产的检验结果Y为各个区间的检验值之和。ΣYi，Σ的循环变量为i，1≤i≤m。<BR><BR>若这批矿产的检验结果与所给标准值S&nbsp;相差太多，就需要再去检验另一批矿产。小T不想费时间去检验另一批矿产，所以他想通过调整参数W&nbsp;的值，让检验结果尽可能的靠近标准值S，即使得S-Y&nbsp;的绝对值最小。请你帮忙求出这个最小值。&nbsp; 

 
 # 输入格式 
第一行包含三个整数n&nbsp;，m，S，分别表示矿石的个数、区间的个数和标准值。&nbsp;接下来的n&nbsp;行，每行&nbsp;2&nbsp;个整数，中间用空格隔开，第i+1&nbsp;行表示&nbsp;i&nbsp;号矿石的重量&nbsp;wi&nbsp;和价值vi&nbsp;。&nbsp;<BR>接下来的m&nbsp;行，表示区间，每行2&nbsp;个整数，中间用空格隔开，第i+n+1&nbsp;行表示区间[Li,&nbsp;Ri]的两个端点&nbsp;Li&nbsp;和Ri&nbsp;。注意：不同区间可能重合或相互重叠。&nbsp; 

 
 # 输出格式 
输出只有一行，包含一个整数，表示所求的最小值。&nbsp; 

 
 # 提示 
对于10%&nbsp;的数据，有&nbsp;1&nbsp;≤n&nbsp;，m≤10；&nbsp;<BR>对于30%&nbsp;的数据，有&nbsp;1&nbsp;≤n&nbsp;，m≤500&nbsp;；&nbsp;<BR>对于50%&nbsp;的数据，有&nbsp;1&nbsp;≤n&nbsp;，m≤5,000；&nbsp;<BR>对于70%&nbsp;的数据，有&nbsp;1&nbsp;≤n&nbsp;，m≤10,000&nbsp;；&nbsp;<BR>对于100%的数据，有&nbsp;1&nbsp;≤n&nbsp;，m≤200,000，0&nbsp;&lt;&nbsp;wi,&nbsp;vi≤10^6，0&nbsp;&lt;&nbsp;S≤10^12，1&nbsp;≤Li&nbsp;≤Ri&nbsp;≤n&nbsp;。&nbsp; 
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
3 3 </td><td>10 

对样例的解释
当W 选4 的时候，三个区间上检验值分别为 20、5 、0 ，这批矿产的检验结果为 25，此时与标准值S 相差最小为10。 </td></tr></table>
