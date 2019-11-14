# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;小Q玩开采金钱游戏因为赚了太多钱，而这些钱又没有用，所以他相当愤怒，投诉了出品游戏者。所以游戏出品者就推出了《购买气球》这一款游戏，这一游戏是可以使用经营餐厅游戏获得的钱的。<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小Q在经营餐厅中赚下了Money元，这些钱可以用来从商店买红色或者蓝色的气球，打破一个红色气球可以让分数score变为原来的red倍，打破一个蓝色的气球可以让分数score加上blue，每当你的分值score到达一个值win[i]（score&gt;=win[i]）可以获得额外奖励金钱gold[i]。<BR>&nbsp;&nbsp;&nbsp;&nbsp;当然，开始小Q得到的分值为0。<BR>&nbsp;&nbsp;&nbsp;&nbsp;注：任何操作或奖励前后都不能欠钱（money不能小于0）。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行八个正整数Money，N，S1，S2，cost1，cost2，red，blue。表示有N个奖励方案，商店有S1个红色气球，S2个蓝色气球，买一个红色气球要花费cost1元，买一个蓝色气球需要cost2元。Money,red,blue意思为题目所示。（&nbsp;1&nbsp;&lt;=&nbsp;red&nbsp;&lt;=&nbsp;3&nbsp;,1&nbsp;&lt;=&nbsp;blue&nbsp;&lt;=&nbsp;10&nbsp;）<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行两个正整数win[i]，gold[i]，意义如题目所示。（&nbsp;1&nbsp;&lt;=&nbsp;win[i]&nbsp;&lt;=&nbsp;10^8&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;gold[i]&nbsp;&lt;=&nbsp;10^6&nbsp;）<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一个数Max表示最多能得到的分数。（我们无视金钱）<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;样例中有5个红色气球和6个蓝色气球，红色气球和蓝色气球都要2元，红色气球能让分值成为3倍，蓝色气球能让分值加上10。<BR>&nbsp;&nbsp;&nbsp;&nbsp;样例先买蓝色气球一个，用了2元，没钱了。打破它，分值加10，变为10，由于到达了奖励方案1和奖励方案2的值(win[i])，被奖励2（gold[1]&nbsp;+gold[2]=1+1=2）元，这两元用来买红色气球，打破它，分值变为3倍，即30，钱用完。<BR>40%的数据：1&nbsp;&lt;=&nbsp;S1&nbsp;&lt;=&nbsp;5&nbsp;，1&nbsp;&lt;=&nbsp;S2&nbsp;&lt;=&nbsp;10<BR>100%的数据：1&nbsp;&lt;=&nbsp;Money&nbsp;&lt;=&nbsp;10^6&nbsp;，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;100&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;S1&nbsp;&lt;=&nbsp;10&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;s2&nbsp;&lt;=&nbsp;1000<BR> 
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
<tr><td>2 2 5 6 2 2 3 10
1 1
2 1
</td><td>30
</td></tr></table>
