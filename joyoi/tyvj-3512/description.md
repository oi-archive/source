# 

 
 # 题目描述 
<p>
　　问题：两个水壶倒水。  <br>　　有两个无刻度标志的A水壶和B水壶，其容量分别为x升水和y升水（x,y均为整数，且均小于等于100）。设另有一个水缸，可以用来向水壶灌水，也可将水壶的水倒入水缸，两个水壶之间，可以相互灌水。初始时，A水壶为满壶，B水壶为空壶，问：如何通过倒水或灌水操作，用最少步数能在B水壶中量出z升（z<=100）水来。</p> 

 
 # 输入格式 
<p>
　　一行，三个数，分别是A水壶容量，B水壶容量，以及要在B水壶中量出的z升水。</p> 

 
 # 输出格式 
<p>
　　一个整数，倒水的最少步数。若无法倒出，则输出“no”。</p> 

 
 # 提示 
<p>
样例的一个最少倒水步骤：<br>  10   0<br>   3   7<br>   3   0<br>   0   3<br>  10   3<br>   6   7<br>   6   0<br>   0   6<br>  10   6<br>   9   7<br>   9   0<br>   2   7<br>   2   0<br>   0   2</p> 
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
<tr><td>10 7 2</td><td>13</td></tr></table>
