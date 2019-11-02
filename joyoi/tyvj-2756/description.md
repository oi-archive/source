# 

 
 # 题目描述 
<p>
小y最近在研究一个再普通不过的东西——条形码。<br>他发现：条形码是一种由“亮条（light bar）”和“暗条（dark bar）”交替出现，且以“暗条”起头的符号。每个“条”（bar）都是若干个单位宽。图1给出了一个含4个“条”的条形码，它延续了1+2+3+1=7个单位宽。<br>一般情况下，BC(n,k,m)是一个包含所有由k个“条”，总宽度正好为n个单位，每个“条”的宽度至多为m个单位的性质的条形码组成的集合。例如：图1的条形码属于BC(7,4,3),而不属于BC(7,4,2)。<br><br><center><img src="/source/joyoi/tyvj-2756/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc1Ni9wcm9ibGVtc19pbWFnZXMvMzI2NS9waG90by5qcGc=.jpg"></img></center><br>图2显示了集合BC(7,4,3)中的所有16个符号。1表示暗，0表示亮。图中的条形码已按字典顺序排列。冒号左边的数字为“条形码”的编号。图1中条形码的在BC(7,4,3)中的编号为4。</p> 

 
 # 输入格式 
<p>
输入文件的第一行为3个数，依次为n，k，m（1<=n,k,m<=30）。<br>第二行为一个整数s（s<=100）。<br>而后s行中，每行为一个符合BC(n,k,m)定义的条形码。<br></p> 

 
 # 输出格式 
<p>
输出文件的第一行为符合BC(n.k,m)定义的条形码的个数。<br>而后s行中，每一行为输入文件中对应的条形码的编号。<br></p> 

 
 # 提示 
<p>
共10组测试数据，保证30%的数据n,k,m<15。</p> 
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
<tr><td>7 4 3
5
1001110
1110110
1001100
1001110
1000100
</td><td>16
4
15
3
4
0</td></tr></table>
