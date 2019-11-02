# 

 
 # 题目背景 
话说一天，铃木美术馆又要添新家伙了，是SRC的巨幅画像<BR>不幸的是，怪盗基德又发来了挑战书……&nbsp;<BR>"以明珠装饰的party<BR>&nbsp;Kidd一定来助兴<BR>&nbsp;为大家带来魔术的神奇<BR>&nbsp;公大家笑纳<BR>&nbsp;差下的祝礼<BR>&nbsp;的确需要补上<BR>&nbsp;数到10，睁开眼睛<BR>&nbsp;列出的就是我的开场白<BR>&nbsp;の的漩涡是我的中心<BR>&nbsp;最先的语言<BR>&nbsp;大约地表达着我的心意<BR>&nbsp;长长的语言<BR>&nbsp;度量着我的真心<BR>&nbsp;即我想向诸位表达的<BR>&nbsp;是<BR>&nbsp;我对贵馆<BR>&nbsp;的最美的祝福<BR>&nbsp;化为守护天使<BR>&nbsp;身情地为贵馆带来微薄的守护……"<BR>毛利小五郎：“什么东西嘛，话也不通。”<BR>柯南一把抢下挑战书：“什么数列？”<BR>毛利：“数列？”<BR>柯南：“有名单吗？”<BR>铃木次郎吉：“有……”<BR>铃木:“可是，被人偷换了……”<BR>名单反面有一行&nbsp;&nbsp;k=？？<BR>每个名字后面被添了一个数字<BR>“やっぱり　そうなんだ” 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;给定一个长为n的数列，和一个k值。求以k为公差的等差数列的最大长度。这个数列应该是原数列的一段子序列(可以不连续)。例如对于数列1&nbsp;&nbsp;2&nbsp;&nbsp;3&nbsp;&nbsp;4&nbsp;&nbsp;5，1&nbsp;&nbsp;4&nbsp;&nbsp;5就是它的一个子序列。这里子序列元素的先后顺序必须和它们在原数列中的先后顺序相一致。 

 
 # 输入格式 
共两行，第一行两个数n和k，n是原数列长度，k是要选择的子序列的公差。<BR>第二行为n个整数。 

 
 # 输出格式 
一行，为符合要求的子序列的最大长度。 

 
 # 提示 
最长的数列为1&nbsp;2&nbsp;或3&nbsp;4，长度为2。<BR>30％的数据，n≤100，|k|≤10<BR>50％的数据，n≤5000，|k|≤500<BR>100％的数据，n≤100000，|k|≤1000<BR>每个数绝对值小于等于100000创意来自SRC，题目叙述来自Lchang，数据和标程来自Kib 
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
<tr><td>8 1
1 4 1 3 1 4 1 2
</td><td>2
</td></tr></table>
