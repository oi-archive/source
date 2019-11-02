# 

 
 # 题目描述 
<p>
农夫John准备扩大他的农场,他正在考虑N (1 <= N <= 50,000) 块长方形的土地. 每块土<br>地的长宽满足(1 <= 宽 <= 1,000,000; 1 <= 长 <= 1,000,000).<br><br>每块土地的价格是它的面积,但FJ可以同时购买多快土地. 这些土地的价格是它们最大的长乘以<br>它们最大的宽, 但是土地的长宽不能交换. 如果FJ买一块3x5的地和一块5x3的地,则他需要<br>付5x5=25.<br><br>FJ希望买下所有的土地,但是他发现分组来买这些土地可以节省经费. 他需要你帮助他找到最小<br>的经费.<br><br></p> 

 
 # 输入格式 
<p>
* 第1行: 一个数: N<br><br>* 第2..N+1行: 第i+1行包含两个数,分别为第i块土地的长和宽<br><br></p> 

 
 # 输出格式 
<p>
<br>* 第一行: 最小的可行费用.<br><br><br></p> 

 
 # 提示 
<p>
<br>FJ分3组买这些土地: 第一组:100x1, 第二组1x100, 第三组20x5 和 15x15 plot. 每组<br>的价格分别为100,100,300, 总共500.<br></p> 
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
<tr><td>4
100 1
15 15
20 5
1 100

输入解释:

共有4块土地.

</td><td>
500
</td></tr></table>
