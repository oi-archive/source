# 

 
 # 题目描述 
<p>唔&hellip;&hellip;xzj终于完成了他的研究计划，于是他去商场上转了一圈，发现了**(禁止含有不文明词汇)lwy。此子是只土豪，喜欢炫阔，于是买东西专门拣贵的买。然而碰巧的是，商店做活动要求买东西是按顺序的。也就是说，买过一个物品之后，可供选择购买的物品只有规定的几种&hellip;&hellip;so，lwy**了。这时，xzj已经暗暗计算起lwy大土豪能够花掉的最多钱。</p> 

 
 # 输入格式 
<p>第一行两个整数N和M，表示物品个数（标号0~n）和商场的规定个数（N&le;2*10<sup>5</sup>，M&le;1*10<sup>6</sup>）。</p>

<p>接下来一行N个数，表示每个物品的价格W。</p>

<p>接下来M行，按顺序每行两个正整数u和v，表示买完物品u后可以买物品v。</p>

<p>最后一行一个数t，表示lwy将从第t件物品开始购买。</p> 

 
 # 输出格式 
<p>最大的价格。</p> 

 
 # 提示 
<p>购买顺序是1-&gt;2-&gt;3-&gt;4</p> 
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
<tr><td>5 4
10 9 22 47 16
1 2
2 3
3 4
3 5
1
</td><td>88</td></tr></table>
