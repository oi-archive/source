# 

 
 # 题目描述 
一位勇士去攻打森林中的魔王。勇士的体力、魔力均为k。当发动攻击时，勇士会消耗m点体力和n点魔力，攻击范围为(m^2+n^2)。当且仅当(n^2-m*n-m^2)^2=1且攻击范围最大时，魔王会被击倒；但如果勇士消耗的魔力多于体力(即n&gt;m)或剩余体力小于0时，勇士会壮烈牺牲。那么，在保全自己的前提下，勇士应如何分配体力和魔力，才能尽快击倒魔王？此时攻击范围是多大？<BR>注：a^b表示a的b次方。<BR> 

 
 # 输入格式 
输入一个正整数k。 

 
 # 输出格式 
输出三行，第一行为消耗的体力，第二行为消耗的魔力，第三行为攻击范围。 

 
 # 提示 
数据范围：<BR>&nbsp;30%:1≤k≤10^2;<BR>&nbsp;60%:1≤k≤10^5;<BR>100%:1≤k≤10^100;(没错，是100)<BR><BR> 
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
<tr><td>3
</td><td>3
2
13
</td></tr></table>
