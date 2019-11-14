# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Matrix67和Shadow正在做一个小游戏。<BR>&nbsp;&nbsp;&nbsp;&nbsp;桌子上放着两堆糖果，Matrix67和Shadow轮流对这些糖果进行操作。在每一次操作中，操作者需要吃掉其中一堆糖果，并且把另一堆糖果分成两堆（可以不相等）留给对方操作。游戏如此进行下去，糖果数会越来越少，最后必将出现这样一种情况：某人吃掉一堆糖果后发现另一堆里只剩一块糖果不能再分了。游戏规定此时该操作者吃掉最后这一块糖果从而取胜。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这个游戏是不公平的。对于任意一种初始状态，总有一方有必胜策略。所谓有必胜策略是指，无论对方如何操作，自己总有办法取胜。<BR>&nbsp;&nbsp;&nbsp;&nbsp;Matrix67和Shadow将进行10次游戏，每一次游戏中总是Matrix67先进行操作。Matrix67想知道每一次游戏中谁有必胜策略。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入数据一共10行，每行有两个用空格隔开的正整数，表示一次游戏开始时桌子上两堆糖果分别有多少个。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于50%的数据，这些正整数均不超过100；<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于70%的数据，这些正整数均不超过10&nbsp;000；<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，这些正整数均不超过10&nbsp;000位。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出十行字符串。这些字符串只能是“Matrix67”或“Shadow”，它们表示对应的十行输入数据中有必胜策略的一方。<BR>&nbsp;&nbsp;&nbsp;&nbsp;请注意大小写。 

 
 # 提示 
Matrix67原创 
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
<tr><td>1 1
1 2
1 3
1 4
1 5
2 1
2 2
2 3
2 4
2 5
</td><td>Matrix67
Matrix67
Matrix67
Matrix67
Matrix67
Matrix67
Shadow
Shadow
Matrix67
Matrix67
</td></tr></table>
