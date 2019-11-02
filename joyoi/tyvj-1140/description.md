# 

 
 # 题目背景 
&nbsp;一阵狂风吹过&nbsp;<BR>&nbsp;飘飘乎居士第一次来到oibh就遇到了麻烦<BR>&nbsp;只听“pong”的一声，飘飘乎居士降落了！！！ 

 
 # 题目描述 
&nbsp;&nbsp;为了营救被困的MM，飘飘乎居士冒着生命危险来到oibh大门，守门的是一个机器人，只有用智慧战胜机器人，<BR>飘飘乎居士才能顺利地进入oibh拯救MM。<BR>&nbsp;&nbsp;于是，飘飘乎居士开始和机器人来了一场智慧的较量，机器人和飘飘乎居士会随机得到一个数字a，b。由数字较大<BR>的一方首先开始操作，他可以把自己手中的数减去任意一个质数或者1，得到一个新的数，直到谁手中的数先变为0即<BR>为获胜者。(这里飘飘乎居士和机器人都采用最优的办法）。<BR>&nbsp;&nbsp;飘飘乎居士想知道他能否成功地拯救可爱的MM。所有的动作必须要快，因为飘飘乎居士想要快点把被困的MM救出。<BR>所以给你的时间不会超过1S 

 
 # 输入格式 
第一行一个数据n，表示有n组测试数据，(N&lt;=10)。<BR>以下n行，分别为飘飘乎居士得到的数字a和机器人得到的数字b.<BR>输入数据保证a与b不相等。<BR>所有数据小于maxlongint。 

 
 # 输出格式 
对于每个输入数据输出一行答案，如果飘飘乎居士能够成功进入oibh，则输出'YES'，否则输出'NO'。 

 
 # 提示 
对于3&nbsp;2，飘飘乎居士先报3，所以他就直接取胜了。<BR>对于1&nbsp;2，机器人先报2，所以飘飘乎居士就失败了。<BR>对于4&nbsp;3，飘飘乎居士先报1，但是机器人直接报3，所以飘飘乎居士失败。<BR>对于6&nbsp;1，飘飘乎居士先报3，机器人直接报1，所以飘飘乎居士就失败了。<BR>对于7&nbsp;8，机器人先报5，飘飘乎居士直接报7，所以飘飘乎居士获胜。飘飘乎居士——violet&nbsp;hill 
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
<tr><td>5
3 2
1 2
4 3
6 1
7 8</td><td>YES
NO
NO
NO
YES</td></tr></table>
