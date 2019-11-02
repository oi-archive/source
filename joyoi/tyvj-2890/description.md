# 

 
 # 题目描述 
<p>
　　排列与组合是常用的数学方法，其中组合就是从n个元素中抽出r个元素(不分顺序且r <＝ n)，我们可以简单地将n个元素理解为自然数1，2，…，n，从中任取r个数。<br>　　现要求你不用递归的方法输出所有组合。<br>　　例如n＝5，r＝3，所有组合为：<br>    l 2 3<br>    l 2 4<br>    1 2 5<br>    l 3 4<br>    l 3 5<br>    1 4 5<br>    2 3 4<br>    2 3 5<br>    2 4 5<br>    3 4 5<br></p> 

 
 # 输入格式 
<p>
　　一行两个自然数n、r( 1 < n < 21，1 <＝ r <＝ n )。</p> 

 
 # 输出格式 
<p>
　　所有的组合，每一个组合占一行且其中的元素按由小到大的顺序排列，每个元素占三个字符的位置，所有的组合也按字典顺序。</p> 
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
<tr><td>5 3</td><td>  1  2  3
  1  2  4
  1  2  5							
  1  3  4
  1  3  5
  1  4  5
  2  3  4
  2  3  5
  2  4  5
  3  4  5

（注意输出格式，每个输出数值占用3个字符位置，即用输出格式控制语句：write(a:3) ，a表示输出变量）</td></tr></table>
