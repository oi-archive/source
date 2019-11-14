# 

 
 # 题目背景 
<p>公元2010年03月09日上午第四节课，数学老师正在讲科学计数法关于绝对值小于1的表示方法。某只猪灵光一闪，哦哈！一道题就新鲜出笼了&hellip;&hellip;<br />
【小知识】&nbsp;将一个数字表示成&nbsp;（a&times;10的n次幂的形式，即&nbsp;a*10^n），其中1&le;|a|＜10，n表示整数，这种记数方法叫科学记数法。</p> 

 
 # 题目描述 
<p>给你一些数（0&le;整数部分的绝对值＜maxlongint），然后用科学计数法表示这些数。</p> 

 
 # 输入格式 
<p>有若干行实数<br />
『注意事项』<br />
⒈&nbsp;如果数A（1&le;|A|＜10），直接输出<br />
⒉&nbsp;如果数A等于0，直接输出<br />
⒊&nbsp;如果数A（|A|＜1），输出格式是&nbsp;a.b*10^(-d)<br />
⒋&nbsp;如果数A（10&le;|A|＜100），输出格式是&nbsp;a.b*10<br />
⒌&nbsp;如果数A（|A|&ge;100），输出格式是&nbsp;a.b*10^d<br />
⒍&nbsp;如果数A（|A|＜1或|A|&ge;10）且a=1，b=0，那么直接输出&nbsp;10^d&nbsp;或&nbsp;10^(-d)<br />
⒎&nbsp;如果数A（|A|＜1或|A|&ge;10）且a=-1，b=0，那么直接输出&nbsp;-10^d&nbsp;或&nbsp;-10^(-d)</p> 

 
 # 输出格式 
<p>若干行用科学计数法表示后的数</p> 

 
 # 提示 
<p>此题虽水却要注意细节哦，o(&cap;_&cap;)o&nbsp;哈哈天蝎的猪_原创出品_转载请注明出处<br />
http://hi.baidu.com/%CC%EC%D0%AB%B5%C4%D6%ED/blog/item/78f82cc21b893d100ff47774.html</p> 
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
<tr><td>0
1.0001
0.00001
-0.00001
-100000000
130
0.013</td><td>0
1.0001
10^(-5)
-10^(-5)
-10^8
1.3*10^2
1.3*10^(-2)</td></tr></table>
