# 

 
 # 题目描述 
<p>
邀请卡分发（Deliver.pas\c\cpp） 

 
 # 输入格式 
<p>
　　输入文件Deliver.in的第一行包含两个整数P和Q （1<=P,Q<=50000）。P为车站总数（包含AMS公司），Q为公共汽车线路数目。接下来有Q行，每行表示一条线路，包含三个数：起点，终点和车费。所有线路上的车费是正整数，且总和不超过1000000000。并假设任何两个车站之间都可到达。</p> 

 
 # 输出格式 
<p>
　　输出文件Deliver.out仅有一行为公司花在分发邀请卡员工交通上的最少费用。</p> 
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
<tr><td>【输入样例1】
2 2
1 2 13
2 1 33

【输入样例2】
4 6
1 2 10
2 1 60
1 3 20
3 4 10
2 4 5
4 1 50
</td><td>【输出样例1】
46

【输出样例2】
210</td></tr></table>