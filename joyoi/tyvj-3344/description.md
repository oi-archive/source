# 

 
 # 题目描述 
<p>
最佳路线（line.pas\c\cpp） <br><br>【背景】<br>　　为了封印锁妖塔，景天一行人要寻找灵珠,拯救苍生。<br><br>【题目描述】<br>　　路途中可能会经过n个地点（编号分别为1。。N），其中K个是藏有灵珠的。（每个地点最多只有一颗灵珠）由于大量妖怪从锁妖塔逃出，某些城市之间的道路变得不安全，只剩m条道路可以通行。景天想知道在最快需要多长时间才能把灵珠收集完？（假设出发和结束点均为编号W（W<=N）的地点）<br></p> 

 
 # 输入格式 
<p>
　　输入文件line.in第一行两个数n，m<br>　　接下来一行是W<br>　　接下来m行，每行两个正整数A，B，T，表示编号为A，B的两地点之间有一条无向的路，需要时间T才能走完。<br>　　接下来一行是K(K<=N)<br>　　再下一行K个数，表示藏有灵珠的地点编号。<br></p> 

 
 # 输出格式 
<p>
　　输出文件line.out结果输出到文件line.out中。<br>　　若能收集完,输出最少时间,若不能收集完输出-1<br></p> 

 
 # 提示 
<p>
【数据范围】<br>　　对于30%的数据：1<=n<=10<br>　　对于100%的数据：1<=n<=100,1<=M<=N*N,K<=10<br></p> 
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
<tr><td>4 3
1
1 2 2
2 3 4
3 4 1
1
4
</td><td>14</td></tr></table>
