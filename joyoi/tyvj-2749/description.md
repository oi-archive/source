# 

 
 # 题目描述 
<p>
Trash（垃圾）(trash.pas/c/cpp)<br><br>【问题描述】<br><br>    你现在是当地的一家垃圾回收站的首席执行官（ CEO ）。你的工作之一就是处理回收的垃圾，把它分类，以便循环利用。这些垃圾装在n个容器中，每一容器装了n种垃圾，给出容器中垃圾的数量，找一种最佳方法把这些垃圾分类。分类垃圾就是把每一种垃圾单独放在一个容器中，容器假设有无限大。把一个单位的垃圾从容器i移到容器j，如果i <> j,则成本为1，否则为0.你必须找一种方法，使总成本最小。 <br></p> 

 
 # 输入格式 
<p>
     第一行为容器总数 n (1 <= n <= 150),以下每行描述n个容器，每一个容器中的每一种垃圾的数量（数量不大于100）  </p> 

 
 # 输出格式 
<p>
     输出垃圾分类的最小成本。 <br><br></p> 
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
62 41 86 94 
73 58 11 12 
69 93 89 88 
81 40 69 13 
</td><td>650</td></tr></table>
