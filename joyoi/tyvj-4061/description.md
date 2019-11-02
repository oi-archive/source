# 

 
 # 题目描述 
<p>为了提高自己低得可怜的智商，奶牛们设计了一个新的猜数游戏，来锻炼她们的逻辑推理能力。游戏开始前，一头指定的奶牛会在牛棚后面摆N堆干草，每堆有若干捆，并且没有哪两堆中的草一样多。所有草堆排成一条直线，从左到右依次按1至N编号。然后，游戏开始。另一头参与游戏的奶牛会问那头摆干草的奶牛Q个问题，问题的格式如下：</p>

<p>编号为Ql至Qh(1&nbsp;&le;&nbsp;Ql&nbsp;&le;&nbsp;Qh&nbsp;&le;&nbsp;N)的草堆中，最小的那堆里有多少捆草？</p>

<p>对于每个问题，摆干草的奶牛回答一个数字A，但或许是不想让提问的奶牛那么容易地得到答案，又或许是她自己可能记错每堆中干草的捆数，总之，她的回答不保证是正确的。现在请你帮助提问的奶牛判断一下，摆干草的奶牛的回答是否有自相矛盾之处。</p> 

 
 # 输入格式 
<p>输入第一行包含两个整数N和Q，以下Q行每行包含三个整数Q1、Qh和A分别表示相应的问题及其答案。</p> 

 
 # 输出格式 
<pre>
输出包含一个整数，表示该问题的答案与之前的回答有冲突。如果没有出现冲突，则输出0。</pre> 

 
 # 提示 
<p>对于40%的数据，有1&nbsp;&le;&nbsp;Q&nbsp;&le;&nbsp;1000；</p>

<p>对于100%的数据，有1&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;1000000，1&nbsp;&le;&nbsp;Q&nbsp;&le;&nbsp;25000，1&nbsp;&le;&nbsp;A&nbsp;&le;&nbsp;1000000000。</p> 
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
<tr><td>20 4
1 10 7
5 19 7
3 12 8
11 15 12
</td><td>3
</td></tr></table>
