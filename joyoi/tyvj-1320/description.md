# 

 
 # 题目描述 
贵系与人大新闻系合办的新生舞会上，由于种种原因，作为贵班围观团团长的Will决定虽然自己不跳舞，但是也应该服务大家。于是Will准备了好多好多的果汁提供给大家（当然包括各自的舞伴或者家属）。Will将所有的果汁都倒入了N个从0到N-1标号的杯子里，每一个杯子的容量都是C，而第i号杯子里一开始将被预先倒入bottle[i]的饮料。作为一个有经济头脑的人，Will当然觉得不能白提供饮料呀，怎么也得卖，但是卖就有个卖法——比如怎么定价。Will发现，一杯果汁的价格是和杯子里装有的果汁量紧密相关的，具体而言，如果对于第i个杯子里装了x的果汁（0&lt;=x&lt;=C），那么这杯果汁可以卖出的价格就是price[x]。想到这里Will发现了一件很悲剧的事情，由于Will已经把所有果汁都倒进杯子里了，总不能再全部倒回去重新分配吧？（那种大桶的果汁瓶的瓶口都很小的，而杯子又很多……）<BR>但是聪明的Will总是有解决方案的：Will每次选择两个不同的杯子A和B，然后将B里的果汁倒向杯子A，直到B空了，或者A满了为止。<BR>Will可以做无数多次这样的操作，现在Will想知道，假设他能够把所有果汁都卖出去，那他最多能赚多少钱呢？<BR> 

 
 # 输入格式 
第一行两个数，N和C<BR>第二行N个数表示bottle[i](0&lt;=i&lt;N)<BR>第三行C+1个数表示price[i](0&lt;=i&lt;=C)<BR> 

 
 # 输出格式 
一行一个整数，表示做多能赚的钱的数量<BR> 

 
 # 提示 
1&lt;=C&lt;=49<BR>1&lt;=N&lt;=15<BR>0&lt;=bottle[i]&lt;=C<BR>0&lt;=price[i]&lt;=1000000<BR><BR>30%&nbsp;N&nbsp;&lt;=&nbsp;4<BR>50%&nbsp;N&nbsp;&lt;=&nbsp;6<BR>70%&nbsp;N&nbsp;&lt;=&nbsp;11<BR>100%&nbsp;N&nbsp;&lt;=&nbsp;15<BR> 
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
<tr><td>输入样例1
2 10
5 8
0 0 0 0 0 0 0 0 0 0 10

输入样例2
4 10
4 5 3 7
14 76 12 35 6 94 26 3 93 90 420

</td><td>输出样例1
10

输出样例2
625
</td></tr></table>
