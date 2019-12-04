# 

 
 # 题目描述 
<p>
	今天Tango班上谢师宴，去吃自助餐~~~<br>	一张很长的桌子上面摆放着很多碟食物，Tango对每一碟食物都评上了味道值（1~10000），越好吃的东西其值越高（这是叫做职业病吧……）<br>	Tango吃东西的方式很奇怪……他只会吃一次，而且是从某一碟食物开始张大嘴吃掉连续碟子的食物。<br>	虽说有这么奇怪的吃饭方式，但是Tango的胃口有限，要尽可能的吃少几碟食物，但是Tango也不想随随便便就吃完，所以就限定了一个味道值总和的下限，现在要求你求出Tango最少要吃多少碟食物才能>=味道值总和的下限。<br></p> 

 
 # 输入格式 
<p>
第一行，有2个整数N和S，分别代表食物的碟数以及味道值总和的下限。<br>（10 < N < 100000，0 < S < 100000000）<br>第二行，有N个整数，分别是各碟食物的味道值。<br>（0 < Pi <= 10000）<br></p> 

 
 # 输出格式 
<p>
只有一行，一个整数，代表Tango最少要吃多少碟食物<br>（假如Tango把所有东西吃完都达不到下限，Tango会很遗憾的一碟都不吃……）。</p> 
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
<tr><td>Sample Input：
10 15
5 1 3 5 10 7 4 9 2 8
Sample Output：
2
Sample Input 2：
5 11
1 2 3 4 5
Sample Output 2：
3
</td><td>（见上）</td></tr></table>
