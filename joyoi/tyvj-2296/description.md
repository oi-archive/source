# 

 
 # 题目描述 
<p>
　　X市的一家化工厂最近购买了一批重量为n克的化学原料。这种原料可以进行A,B两种化学实验,每种实验有其固定的利润及损耗率。已知，1克的原料做 A实验可得利润a元，但有p的损耗; 同样，1 克的原料做B实验可得利润b元，但有q的损耗。<br>　　一次全体实验定义为：将手头现有的全部原料一部分做A实验，另一部分做B实验。其利润为做A 实验的总利润与做B实验的总利润之和。<br>　　于是一个问题摆在面前，若化工厂准备做m次全体实验，那么如何安排每次实验，才能使得总利润最大呢？请你编程解决这个问题。<br><br></p> 

 
 # 输入格式 
<p>
仅1行，依次为：n,m,a,b,p,q<br>其中n,m,a,b为整数，且0<n<10000, 0<m<=30, 0<a,b<=1000，0<p<1, 0<q<1。<br><br></p> 

 
 # 输出格式 
<p>
仅一行，为最大利润,并保留五位小数。<br><br></p> 
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
<tr><td>3 100 300 500 0.3 0.6
</td><td>79000.00000</td></tr></table>
