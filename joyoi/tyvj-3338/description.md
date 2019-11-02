# 

 
 # 题目描述 
<p>
aandb（aandb.pas\c\cpp）<br><br>【题目描述】<br>　　SC在奥数班上遇到了难题，老师给奥数班的人每人两个数，然后让他们把两个数的和计算出来。当然，问题并没有想象的那么简单，这两个数是给定进制的，求出的结果也是给定进制的，因此SC就遇到了麻烦，希望你能够帮他设计一个程序解决这个问题。<br></p> 

 
 # 输入格式 
<p>
　　输入文件aandb.in的第一行：三个整数r1、r2、r3分别表示第一个数的进制，第二个数的进制，结果的进制（1 < r1, r2, r3 < 37 ）r1、r2、r3分别严格用一个空格隔开。且该行再没有多余空格。<br>　　第二行：一个r1进制数a，已知a是非负的，且a的十进制表示不超过10^9。<br>　　第三行：一个r2进制数b，范围和a一样。<br>　　注意：a和b的形式一定合法，且a和b中一定没有多余字符。当进制数大于10的时候在一位上10用大写字母A表示，11用B，依此类推。也就是说36进制的时候35用大写字母Z表示。<br></p> 

 
 # 输出格式 
<p>
　　输出文件aandb.out为一行：a+b的r3进制表示</p> 
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
<tr><td>10 10 10
1
1
</td><td>2</td></tr></table>
