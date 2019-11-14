# 

 
 # 题目描述 
<p>
Processor（Processor.pas\c\cpp）<br><br>【题目描述】<br>　　现在有一块超级处理器，需要处理N个A类任务、M个B类任务。<br>　　处理器在连续地处理同一类任务时，运算时间等于任务量的平方。即若连续处理X个A类任务或X个B类任务，则对应<br>的运算时间为X^2。<br>　　处理器在每次进入A或B的工作状态(连续的同一类任务)前，都要花费一定的启动时间。我们用TA和TB分别表示处理器进入工作状态A和工作状态B的启动时间。<br>　　问处理完所有的任务最少需要多少时间。<br></p> 

 
 # 输入格式 
<p>
　　输入文件Processor.in第一行四个正整数N，M，TA，TB。</p> 

 
 # 输出格式 
<p>
　　输出文件Processor.out在第一行输出处理完所有的任务需要的最少运算时间。</p> 

 
 # 提示 
<p>
【数据范围】<br>　　在30%的数据中，1 ≤ N,M ≤ 100<br>　　在50%的数据中，1 ≤ N,M ≤ 1000<br>　　在70%的数据中，1 ≤ N,M ≤ 106<br>　　在100%的数据中，1 ≤ N,M ≤ 109，1 ≤ TA, TB ≤ 100<br></p> 
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
<tr><td>5 6 100 1</td><td>145</td></tr></table>
