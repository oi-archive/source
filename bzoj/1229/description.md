
# Description

<div class="content"><p><span style="font-size: medium">玩具 [Chen Hu, 2006] Bessie的生日快到了, 她希望用D (1 &lt;= D &lt;= 100,000; 70%的测试数据都满足 1 &lt;= D &lt;= 500)天来庆祝. 奶牛们的注意力不会太集中, 因此Bessie想通过提供玩具的方式来使它们高兴. 她已经计算出了第i天需要的玩具数T_i (1 &lt;= T_i &lt;= 50). Bessie的幼儿园提供了许多服务给它们的奶牛程序员们, 包括一个每天以Tc (1 &lt;= Tc &lt;= 60)美元卖出商品的玩具店. Bessie想尽可能的节省钱, 但是Farmer John担心没有经过消毒的玩具会带来传染病(玩具店卖出的玩具是经过消毒的). 有两种消毒的方式. 第1种方式需要收费C1美元, 需要N1个晚上的时间; 第2种方式需要收费 C2美元, 需要N2个晚上的时间(1 &lt;= N1 &lt;= D; 1 &lt;= N2 &lt;= D; 1 &lt;= C1 &lt;= 60; 1 &lt;= C2 &lt;= 60). Bessie在party结束之后把她的玩具带去消毒. 如果消毒只需要一天, 那么第二天就可以拿到; 如果还需要一天, 那么第三天才可以拿到. 作为一个受过教育的奶牛, Bessie已经了解到节约的意义. 帮助她找到提供玩具的最便宜的方法. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第 1 行: 六个用空格隔开的整数 D, N1, N2, C1, C2, Tc </span></p>
<p><span style="font-size: medium">* 第 2..D+1 行: 第 i+1 行包含一个整数: T_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第 1 行: 提供玩具所需要的最小费用. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1 2 2 1 3<br/>
8<br/>
2<br/>
1<br/>
6<br/>
<br/>
输入解释:<br/>
Bessie想开4天的party, 第1天需要8个玩具, 第2天需要2个玩具, 第3天需要1个玩具,<br/>
第4天需要6个玩具. 第一种方式需要$2, 用时1天; 第二种方式需要$1, 用时2天. 买<br/>
一个玩具需要$3.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">35<br/>
输出解释:<br/>
第 1 天   买8个玩具, 花去$24; 送2个玩具去快洗, 6个慢洗.<br/>
第 2 天   取回2个快洗的玩具, 花去$4. 送1个玩具去慢洗.<br/>
第 3 天   取回6个慢洗的玩具, 花去$6.<br/>
第 4 天   取回所有的玩具(与现有的加在一起正好6个), 花去$1. 这样就用了最少的钱.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

