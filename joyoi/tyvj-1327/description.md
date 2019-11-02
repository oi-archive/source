# 

 
 # 题目描述 
残雪取到了毛剑后，经过300多个回合的鏖战，终于打败了门卫。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;于是胜利之后，他们便进入了藏宝洞，见到了神龙见首不见尾的zxb法师。法师见到他们很高兴，便语重心长地对他们说到：这里的宝藏是oi先人们几世几年累积下来和是我4000年来整日泡在网上下载来的。现在，终于派上用场了。但由于2009年的年初，天神dzd发布oi届有史以来最震撼的布告后，这里的宝藏便被上了诅咒，只有能解破宝盒上密码的人才能最终拿到这无尽的oi宝藏。而这需要勇气、信心、毅力。。。。。。<BR>宝盒上是一个4*4的表格矩阵，0~F这16十六进制个数字分布在其中。这十六个数并不是固定的，而是可以移动的。移动规则如下：<BR>1、	横向：<BR>第一行与第二行可以互换。<BR>第二行和第三行可以互换<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第三行和第四行可以互换<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.、纵向：<BR>第一列与第二列可以互换。<BR>第二列和第三列可以互换<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第三列和第四列可以互换<BR>矩阵的下面还有一个格子，需要填入把矩阵中的数字变成如下形式的最短变换次数，只有数字填对才能得到宝藏。<BR><BR>&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;3<BR>4&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;7<BR>8&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;A&nbsp;&nbsp;&nbsp;B<BR>C&nbsp;&nbsp;&nbsp;D&nbsp;&nbsp;&nbsp;E&nbsp;&nbsp;&nbsp;F<BR>所有数据的最短步数不超过50。<BR><BR> 

 
 # 输入格式 
&nbsp;4*4的矩阵，内容为1~F这16个数(每一行的相邻数字之间没有空格)<BR> 

 
 # 输出格式 
一个数，即最短步数<BR> 

 
 # 提示 
所有数据保证有解<BR> 
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
<tr><td>4567
0123
89AB
CDEF

</td><td>1
</td></tr></table>
