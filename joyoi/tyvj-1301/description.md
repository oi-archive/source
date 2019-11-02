# 

 
 # 题目背景 
虽然Winter给予了Summer一次重击，但是Summer没有放弃对能源的渴望，是的，Summer联盟的能源不一定有Winter联盟的能源那么充足。但是Summer的装甲和人员的数量肯定比Winter要多的多。于是，HF下了一条命令：全部人员冲击前线！<BR> 

 
 # 题目描述 
Winter的基地前线可以看成是1条长度为N的防线，Winter每建造一座防御炮i可以看做是给[Bi,Ei]的区间加大了Di的攻击力。<BR>而Summer每一次冲锋则是对一个位置k展开攻势。HF请你做的就是输出从k进攻需要受到多大的攻击。（&nbsp;从k受到的攻击&nbsp;=&nbsp;所有可以攻击到k的防御炮的攻击力总和&nbsp;）<BR> 

 
 # 输入格式 
第一行两个数整数N,M，表示防线的长度和发生的情况数。<BR>(&nbsp;1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10^9&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;M&nbsp;&lt;=&nbsp;5&nbsp;*&nbsp;10^4&nbsp;)<BR>接下来M行，每行可以为<BR>W&nbsp;b&nbsp;e&nbsp;d&nbsp;表示Winter建造了一座防御炮，对b至e的区间加大了d的攻击力。<BR>S&nbsp;k&nbsp;表示Summer在k发起攻势。<BR> 

 
 # 输出格式 
对于Summer每次攻击，你要输出k处受到了多少攻击。<BR>每行一个数&nbsp; 

 
 # 提示 
1&lt;=bi&lt;=ei&lt;=N<BR>-3000&nbsp;&lt;=&nbsp;di&nbsp;&lt;=&nbsp;3000&nbsp;<BR>输入均为整数From&nbsp;EZ_gx/EZ_lzh 
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
<tr><td>1 2
W 1 1 1
S 1
</td><td>1
</td></tr></table>
