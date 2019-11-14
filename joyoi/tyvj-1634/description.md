# 

 
 # 题目背景 
此题为taophee专辑中的第三题，水题。 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在一阵头晕目眩后，Taophee来到了一个神奇土地上。Taophee发现了一张古人留下的冒险岛的地图，于是勇敢的Taophee就想森林进发了......<BR>&nbsp;&nbsp;&nbsp;&nbsp;可是，当Taophee来到了森林的入口处时，一扇坚硬的门挡住了他的去路。丛林守护者突然跑出来说：“你是来冒险的吗？”Taophee大声答道：“当然是！”丛林守护者又说：“这冒险岛非常危险，你不害怕吗？”Taophee又答：“我才不怕！我有后盾！”“哈哈哈哈~那好，过了这门，你的冒险路就正式开始了！这扇门并不是一扇普通的门，只有回答对它的问题，它才会打开。祝你好运！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;Taophee走近那扇奇妙的门，门对他说：“我知道世界上一个神秘的数列。”<BR>n&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7<BR>f(n)&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4	<BR>n&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12<BR>f(n)&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6<BR>&nbsp;&nbsp;&nbsp;&nbsp;“这是一个不下降的序列，对于任意正整数n，他将恰好在数列中出现f(n)次。其中f(1)=1。如果你能找到最大的k，使得f(k)=n，我就让你过去！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;Taophee由于知道现在头还很晕所以没有办法编程，而且现在还没有能力召唤YH，所以请你帮他过这一关。 

 
 # 输入格式 
只有一行，包含一个正整数n. 

 
 # 输出格式 
只有一行，包含一个正整数m，为最大的m,使得f(m)=n的值。 

 
 # 提示 
数据范围：<BR>n≤5000 
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
<tr><td>4
</td><td>8
</td></tr></table>
