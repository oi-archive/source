# 

 
 # 题目描述 
<p>
Lambdaland由N个城市组成，任两个城市间都有一条道路相连。 下个月TBL准备参观Lambdaland。他将从城市1开始，以深度优先搜索顺序参观能所有遍历到的城市。 由于TBL是一位十分重要的人物，恐怖分子盯上了他，并在他出发之前炸毁了M条道路。 现在恐怖分子雇佣你写一个程序，求出TBL的参观路线。如果有多解，输出字典序最小的。</p> 

 
 # 输入格式 
<p>
第一行包括两个非负整数N、M。 接下来M行，每行两个整数A、B，表示城市A至城市B的道路被炸毁。</p> 

 
 # 输出格式 
<p>
每行一个整数，第i行的整数表示TBL第i次参观的城市编号。</p> 

 
 # 提示 
<p>
20%的分数，N<=1,000，M<=50,000。<br>50%的分数，N<=30,000，M<=800,000。<br>100%的分数，N<=100,000，M<=1,000,000。 <br>每个城市最多被参观一次，每条道路可被炸毁多次</p> 
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
<tr><td>4 4 
1 2
1 3
2 3
3 4</td><td>
1
4
2
</td></tr></table>
