# 

 
 # 题目背景 
Moe-ing&nbsp;与&nbsp;Psyaomo123联合出题 

 
 # 题目描述 
dota是一款非常流行的著名游戏，Moe-ing最近也迷上了dota。<BR>dota中决定游戏的往往是你的装备（当然技术也重要-&nbsp;-），而装备都是要金钱买的，金钱怎么得到呢，杀死敌方小兵就有钱得，杀死小兵得到的钱也是随机的。Moe-ing有个习惯，每次开始攻击小兵就一定要杀死他（怪习惯）。Moe-ing现在有一个难题：已知有n个小兵，每个小兵的血量，杀死小兵所得的金钱和Moe-ing每次攻击能造成的伤害m（固定的），Moe-ing想要知道他在K次攻击之后最多能得到多少钱。<BR> 

 
 # 输入格式 
第一行3个正整数N,M,K分别表示有n个敌方小兵，Moe-ing每次攻击造成m点伤害和Moe-ing可以攻击几次。<BR>第二行n个正整数&nbsp;第i个数字表示第i个小兵的血量；<BR>第三行n个正整数&nbsp;第i个数字表示杀死第i个小兵可以得到的钱。 

 
 # 输出格式 
输出仅一个数字&nbsp;表示最多可以获得的金钱 

 
 # 提示 
1&lt;=n&lt;=100;&nbsp;m&lt;=10000&nbsp;k&lt;=20<BR>最后输出保证小于maxlongint；<BR>Moe-ing&nbsp;与&nbsp;Psyaomo123 
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
<tr><td>4 50 3
8 20 99 101
2 50 20 1000</td><td>1000</td></tr></table>
