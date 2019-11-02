# 

 
 # 题目描述 
<p>
一共n × m 个硬币，摆成n × m 的长方形。dongdong 和xixi 玩一个游戏，<br>每次可以选择一个连通块，并把其中的硬币全部翻转，但是需要满足存在一个<br>硬币属于这个连通块并且所有其他硬币都在它的左上方(可以正左方也可以正<br>上方)，并且这个硬币是从反面向上翻成正面向上。dongdong 和xixi 轮流操作。<br>如果某一方无法操作，那么他(她) 就输了。dongdong 先进行第一步操作，假<br>设双方都采用最优策略。问dongdong 是否有必胜策略。</p> 

 
 # 输入格式 
<p>
第一行一个数T，表示他们一共玩T 局游戏。接下来是T 组游戏描述。每<br>组游戏第一行两个数n;m，接下来n 行每行m 个字符，第i 行第j 个字符如<br>果是“H” 表示第i 行第j 列的硬币是正面向上，否则是反面向上。第i 行j 列<br>的左上方是指行不超过i 并且列不超过j 的区域。</p> 

 
 # 输出格式 
<p>
对于每局游戏，输出一行。如果dongdong 存在必胜策略则输出“- -”(不含<br>引号) 否则输出“= =”(不含引号)。(注意输出的都是半角符号，即三个符号<br>ASCII 码分别为45,61,95)<br></p> 

 
 # 提示 
<p>
对于40% 的数据，满足1 ≤ n;m ≤ 5。<br>对于100% 的数据，满足1 ≤ n;m ≤ 100，1 ≤ T ≤ 50。<br></p> 
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
<tr><td>32
3
HHH
HHH
2 3
HHH
TTH
2 1
T
H
</td><td>= =
- -
- -</td></tr></table>
