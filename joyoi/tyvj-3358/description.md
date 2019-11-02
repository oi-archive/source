# 

 
 # 题目描述 
<p>
肥鼠的难题（fatmouse.pas\c\cpp） <br><br>【题目描述】<br>　　肥鼠是一个数学天赋很高的孩子。他总能秒杀各种数学考试和各种数学题。每天他总会去用各种数学问题为难可怜的Edward_mj。这不，肥鼠又来了。只见他正色道：“考虑到你弱小的心灵，今天考你一个简单的问题吧。解方程会吧？现在给你一个包含N 个关于X 的方程的方程组，让你求出在前T 个正整数里有多少个能满足该方程组的数字。”<br>　　Edward_mj 听完顿时泪流满面。Orz！今天又被虐了！<br>　　你能帮帮可怜的Edward_mj 吗？</p> 

 
 # 输入格式 
<p>
　　输入文件中fatmouse.in第一行N T ——如肥鼠的话<br>　　接下来N 个二元对(Yi,Zi)，表示这个方程组。<br>　　每个二元对表示gcd(X,Yi)=Zi。其中gcd 表示两个数的最大公约数。<br>　　其中1<=Zi<=Yi<=10^5。</p> 

 
 # 输出格式 
<p>
　　输出文件fatmouse.out一个数，表示在前T 个正整数里面，有多少个数字X 能满足这个方程组。</p> 

 
 # 提示 
<p>
【样例解释】<br>　　有6 和18 符合条件。<br><br>【数据规模】<br>数据序号 　N 　　　T<br>　　1 　　100 　　 10^4<br>　　2 　　10 　　　10^5<br>　　3 　　1 　　　 2*10^9<br>　　4 　　1000 　　10^6<br>　　5 　　1000 　　10^6<br>　　6 　　1000 　　10^6<br>　　7 　　1000 　　2*10^9<br>　　8 　　1000 　　2*10^9<br>　　9 　　1000 　　2*10^9<br>　　10 　 1000 　　2*10^9<br><br>【注意】<br>　　数据保证答案不会等于0。</p> 
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
<tr><td>3 20
2 2
3 3
4 2</td><td>2</td></tr></table>
