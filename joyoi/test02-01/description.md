# 题目背景
  无。
# 问题描述
  加、减、乘、除是最基本的四则元算，小Q在此基础上定义了一种新运算，运算符为“△”，运算规则是：
```
a△b=a×b×(b+1)÷2。
```
如：
```
5△3=5×3×(3+1)÷2=30。
```
想必这样的问题不会难倒你，请你用编程输出a△b的结果。 
# 输入格式
  只有一行，一行用空格隔开的两个整数a和b。
# 输出格式
  只有一行，新运算△的结果。
	
# 提示
* **样例解释**

 【输入输出样例1解释】
 ```
  5△3=5×3×(3+1)÷2=30
	```
* **数据范围**

  -10000≤a,b≤10000，a和b以及运算的结果都为整数。
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
<tr><td>5 3</td><td>30</td></tr></table>
