# 

 
 # 题目描述 
<p>
我们可以用三个正整数x y z来描述一个等差数列：x，x+z，x+2z，…，x+kz(x+kz≤y，x+(k+1)z>y)。<br>给定n个这种形式的等差数列，并且告诉你，在所有的正整数中，最多只有一个数字出现在奇数个等差数列中。你需要算出这个数字是多少，或者不存在,如果存在请输出这个数字是多少及它出现的次数<br></p> 

 
 # 输入格式 
<p>
Input file consists from multiple data sets separated by one or more empty lines.<br>Each data set represents a sequence of 32-bit (positive) integers (references) which are stored in compressed way.<br>Each line of input set consists from three single space separated 32-bit (positive) integers X Y Z and they represent following sequence of references: X, X+Z, X+2*Z, X+3*Z, …, X+K*Z, …(while (X+K*Z)<=Y).<br>Your task is to data-mine input data and for each set determine weather data were corrupted, which reference is occurring odd number of times, and count that reference.</p> 

 
 # 输出格式 
<p>
For each input data set you should print to standard output new line of text with either “no corruption” (low case) or two integers separated by single space (first one is reference that occurs odd number of times and second one is count of that reference).</p> 
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
<tr><td>1 10 1
2 10 1

1 10 1
1 10 1

1 10 1
4 4 1
1 5 1
6 10 1</td><td>
1 1
no corruption
4 3</td></tr></table>
