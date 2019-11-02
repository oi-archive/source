# 

 
 # 题目背景 
｛*总背景*｝<BR>经过与Guiolk的战争，Summer&nbsp;和&nbsp;Winter&nbsp;都浪费了大量的能源。<BR>公元3002年9月，Summer&nbsp;联盟：<BR>总控部：“主星球西部电力能源不足，南方水力也不够了。”<BR>HF：“那就从能源部调资源就行了。以后再要动用能源不用经过我的同意了！”<BR>总控部：“可是能源部能源不足了……”<BR>“什么，有人贪污吗？”<BR>“Guiolk入侵的时候，曾经用微子轰击过我们的能源基地，我们多数的能源已经与微子反应了……”<BR>“那Winter那边呢？”<BR>“他们利用光能，很有可持续性，如果用他们的能源，我们十万年也不用愁了……”<BR>HF陷入了沉思……&nbsp;<BR><BR>一个月后。Winter联盟通讯员：“Summer联盟方向出现大量战舰！”<BR>“孜孜”（屏幕被干扰），屏幕上出现HF，HF：“我的确不想破坏我们之间的联盟，但经调查，你们趁上次战争之际抢夺了我们大量的资源，战争中也不肯出力，所以我认为你破坏了我们之间的联盟，叛徒应当被毁灭！不是吗？”<BR> 

 
 # 题目描述 
上万辆的战舰缓慢开进，PL按动了一个蓝色的按钮：“我们应当让他们先尝些苦头。”原来，上次在巨大的爆炸中，PL发现了一种很强的能量，经过PL与许多科学家的研究，这种能量可以让物体穿越空间。<BR>于是，PL将这种能量和一颗巨型炸弹控制在一起，以便对敌人进行攻击。<BR>现在的问题是在什么地方放置炸弹可以让敌人受到最重的打击。<BR>可以把敌人一艘战舰看做平面上的一个点，那么炸弹的爆炸范围便是平面上的一个圆（圆心自然是炸弹了），在圆上和圆内的战舰都会瞬间被摧毁。<BR>当然由于现在这种能量还不能很好的控制，所以只可以将炸弹传送到一条已知直线上，由于地图已经被处理，所以保证这条直线与X轴平行。<BR>每个战舰都有一个价值，由于有的战舰是PL的，所以炸毁战舰价值可能为负，PL请你做的是输出最大的摧毁值。<BR>{&nbsp;摧毁值&nbsp;=&nbsp;所有被炸毁的战舰的价值和&nbsp;}<BR> 

 
 # 输入格式 
第一行，三个自然数N，r，y0。（&nbsp;1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;3&nbsp;*&nbsp;10^4&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;r&nbsp;&lt;=&nbsp;10^&nbsp;9&nbsp;,&nbsp;-10^9&nbsp;&lt;=&nbsp;y0&nbsp;&lt;=&nbsp;10^9&nbsp;）表示敌人战舰数量，炸弹爆炸范围半径和可以放置炸弹的平行于X轴的直线&nbsp;y&nbsp;=&nbsp;y0。<BR>接下来N行，每行三个整数&nbsp;x&nbsp;,&nbsp;y&nbsp;,&nbsp;v&nbsp;。（&nbsp;-10^9&nbsp;&lt;=&nbsp;x&nbsp;,&nbsp;y&nbsp;&lt;=&nbsp;10^9&nbsp;,-5*10^4&nbsp;&lt;=&nbsp;v&nbsp;&lt;=&nbsp;5&nbsp;*&nbsp;10^4&nbsp;&nbsp;）表示一辆战舰的坐标和它的价值。<BR> 

 
 # 输出格式 
一行一个数max，表示最大的的摧毁值。<BR> 

 
 # 提示 
一种传送方案是将炸弹传送到（0，0）。<BR>From&nbsp;EZ_gx/EZ_lzh 
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
<tr><td>2 1415 0
-1000 -1000 1
1000 1000 2
</td><td>3
</td></tr></table>
