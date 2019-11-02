# 

 
 # 题目背景 
<p>NOIP2014提高组第一题</p> 

 
 # 题目描述 
<p>石头剪刀布是常见的猜拳游戏：石头胜剪刀，剪刀胜布，布胜石头。如果两个人出拳一样，则不分胜负。在《生活大爆炸》第二季第8集中出现了一种石头剪刀布的升级版游戏。升级版游戏在传统的石头剪刀布游戏的基础上，增加了两个新手势：</p>

<p>斯波克：《星际迷航》主角之一。</p>

<p>蜥蜴人：《星际迷航》中的反面角色。</p>

<p>&nbsp;</p>

<p>这五种手势的胜负关系如表一所示，表中列出的是甲对乙的游戏结果。</p>

<p>&nbsp;</p>

<p align="center">表一&nbsp;&nbsp;石头剪刀布升级版胜负关系</p>

<table align="center" border="1" cellpadding="0" cellspacing="0" style="width:561px;" width="561">
	<tbody>
		<tr>
			<td style="width:93px;height:77px;">
			<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;乙</p>

			<p>&nbsp;&nbsp;&nbsp;甲对乙的</p>

			<p>甲&nbsp;&nbsp;&nbsp;&nbsp;结果</p>
			</td>
			<td style="width:93px;height:77px;">
			<p align="center">剪刀</p>
			</td>
			<td style="width:94px;height:77px;">
			<p align="center">石头</p>
			</td>
			<td style="width:94px;height:77px;">
			<p align="center">布</p>
			</td>
			<td style="width:94px;height:77px;">
			<p align="center">蜥蜴人</p>
			</td>
			<td style="width:94px;height:77px;">
			<p align="center">斯波克</p>
			</td>
		</tr>
		<tr>
			<td style="width:93px;height:28px;">
			<p align="center">剪刀</p>
			</td>
			<td style="width:93px;height:28px;">
			<p align="center">平</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">输</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">赢</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">赢</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">输</p>
			</td>
		</tr>
		<tr>
			<td style="width:93px;height:27px;">
			<p align="center">石头</p>
			</td>
			<td style="width:93px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">平</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">输</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">赢</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">输</p>
			</td>
		</tr>
		<tr>
			<td style="width:93px;height:28px;">
			<p align="center">布</p>
			</td>
			<td style="width:93px;height:28px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">平</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">输</p>
			</td>
			<td style="width:94px;height:28px;">
			<p align="center">赢</p>
			</td>
		</tr>
		<tr>
			<td style="width:93px;height:27px;">
			<p align="center">蜥蜴人</p>
			</td>
			<td style="width:93px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">平</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">赢</p>
			</td>
		</tr>
		<tr>
			<td style="width:93px;height:27px;">
			<p align="center">斯波克</p>
			</td>
			<td style="width:93px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">&nbsp;</p>
			</td>
			<td style="width:94px;height:27px;">
			<p align="center">平</p>
			</td>
		</tr>
	</tbody>
</table>

<div style="clear:both;">&nbsp;</div>

<p>&nbsp;</p>

<p>现在，小A和小B尝试玩这种升级版的猜拳游戏。已知他们的出拳都是有周期性规律的，但周期长度不一定相等。例如：如果小A以&ldquo;石头-布-石头-剪刀-蜥蜴人-斯波克&rdquo;长度为6的周期出拳，那么他的出拳序列就是&ldquo;石头-布-石头-剪刀-蜥蜴人-斯波克-石头-布-石头-剪刀-蜥蜴人-斯波克-&hellip;&hellip;&rdquo;，而如果小B以&ldquo;剪刀-石头-布-斯波克-蜥蜴人&rdquo;长度为5的周期出拳，那么他出拳的序列就是&ldquo;剪刀-石头-布-斯波克-蜥蜴人-剪刀-石头-布-斯波克-蜥蜴人-&hellip;&hellip;&rdquo;</p>

<p>&nbsp;</p>

<p>已知小A和小B一共进行N次猜拳。每一次赢的人得1分，输的得0分；平局两人都得0分。现请你统计N次猜拳结束之后两人的得分。</p> 

 
 # 输入格式 
<p>输入文件名为rps.in。</p>

<p>第一行包含三个整数：N，NA，NB，分&nbsp;别&nbsp;表&nbsp;示&nbsp;共&nbsp;进&nbsp;行N次猜拳、小A出拳的周期长度，小B出拳的周期长度。数与数之间以一个空格分隔。</p>

<p>第二行包含NA个整数，表示小A出拳的规律，第三行包含NB个整数，表示小B出拳的规律。其中，0表示&ldquo;剪刀&rdquo;，1表示&ldquo;石头&rdquo;，2表示&ldquo;布&rdquo;，3表示&ldquo;蜥蜴人&rdquo;，&nbsp;&nbsp;4表示&ldquo;斯波克&rdquo;。数与数之间以一个空格分隔。</p>

<p>输入样例1：</p>

<p>10&nbsp;5&nbsp;6</p>

<p>0&nbsp;1&nbsp;2&nbsp;3&nbsp;4</p>

<p>0&nbsp;3&nbsp;4&nbsp;2&nbsp;1&nbsp;0</p>

<p>输入样例2：</p>

<p>9&nbsp;5&nbsp;5</p>

<p>0&nbsp;1&nbsp;2&nbsp;3&nbsp;4</p>

<p>1&nbsp;0&nbsp;3&nbsp;2&nbsp;4</p> 

 
 # 输出格式 
<p>输出文件名为rps.out。</p>

<p>输出一行，&nbsp;&nbsp;包含两个整数，以一个空格分隔，分别表示小A、小B的得分。</p>

<p>输出样例1：</p>

<p>6&nbsp;2</p>

<p>输出样例2：</p>

<p>4&nbsp;4</p>

<p>&nbsp;</p> 

 
 # 提示 
<p>对于100%的数据，0&nbsp;&lt;&nbsp;N&nbsp;&le;&nbsp;&nbsp;200，0&nbsp;&lt;&nbsp;NA&nbsp;&nbsp;&le;&nbsp;&nbsp;200，&nbsp;&nbsp;0&nbsp;&lt;&nbsp;NB&nbsp;&nbsp;&le;&nbsp;&nbsp;200。</p> 
