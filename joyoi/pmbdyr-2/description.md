# 题目背景
[@Peter_Matthew](https://www.luogu.org/space/show?uid=59593)在考试时经常```饭```一些低级的错误，例如他经常把1+1算成1,1$\times$1算成2,2$\times$2算成2，他受不了了，只好请你帮他写一个低级计算器。
# 题目描述
给你写在```C++```里的一次方程（这样就避免读入"$\times$","$\div$","$\frac{a}{b}$"这种奇奇怪怪的符号），请你解出对应变量的值。
# 输入格式
第一行有一个整数n和n个字母，分别代表字母及方程个数和变量名。
接下来n行，每行是一串含变量的一次方程（保证所有字母在等式左边，值在等式右边）。
# 输出格式
共n行，每行为一个变量（按输入顺序排列）+等号+对应的值。
# 提示与说明
符号只有![+、-](/source/joyoi/pmbdyr-2/img/aHR0cHM6Ly9jZG4ubHVvZ3Uub3JnL3VwbG9hZC9waWMvMTc0NTcucG5n.png)和![*、&](/source/joyoi/pmbdyr-2/img/aHR0cHM6Ly9jZG4ubHVvZ3Uub3JnL3VwbG9hZC9waWMvMTc0NTkucG5n.png)

保证有解，方便起见n$\leq$5，系数均在-9~9之间。

2018年4月20日就是[@Peter_Matthew](https://www.luogu.org/space/show?uid=59593)的生日了。# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>2 x y
x+y==6
x-y==4
</td><td>x==5
y==1
</td></tr></table>
