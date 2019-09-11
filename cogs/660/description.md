# 题目描述


<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【问题描述】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">是一个非常聪明的孩子，除了国际象棋，他还很喜欢玩一个电脑益智游戏——矩阵游戏。矩阵游戏在一个</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">*<i>N</i></span><span style="font-size:12pt;">黑白方阵进行（如同国际象棋一般，只是颜色是随意的）。每次可以对该矩阵进行两种操作：</span> 
</div>
<div style="margin:0cm 0cm 0pt 54pt;">
<span style="font-size:12pt;">l<span> </span></span><span style="font-size:12pt;">行交换操作：选择矩阵的任意两行，交换这两行（即交换对应格子的颜色）</span> 
</div>
<div style="margin:0cm 0cm 0pt 54pt;">
<span style="font-size:12pt;">l<span> </span></span><span style="font-size:12pt;">列交换操作：选择矩阵的任意两列，交换这两列（即交换对应格子的颜色）</span> 
</div>
<div>
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">游戏的目标，即通过若干次操作，使得方阵的主对角线</span><span style="font-size:12pt;">(</span><span style="font-size:12pt;">左上角到右下角的连线</span><span style="font-size:12pt;">)</span><span style="font-size:12pt;">上的格子均为黑色。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于某些关卡，小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">百思不得其解，以致他开始怀疑这些关卡是不是根本就是无解的！！于是小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">决定写一个程序来判断这些关卡是否有解。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【输入文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">输入文件q</span><span style="font-size:12pt;">matrix.in</span><span style="font-size:12pt;">第一行包含一个整数</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">，表示数据的组数。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">接下来包含</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">组数据，每组数据第一行为一个整数</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">，表示方阵的大小；接下来</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">行为一个</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">*<i>N</i></span><span style="font-size:12pt;">的</span><span style="font-size:12pt;">01</span><span style="font-size:12pt;">矩阵（</span><span style="font-size:12pt;">0</span><span style="font-size:12pt;">表示白色，</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">表示黑色）。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【输出文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">输出文件应包含</span><i><span style="font-size:12pt;">T</span></i><span style="font-size:12pt;">行。对于每一组数据，如果该关卡有解，输出一行</span><span style="font-size:12pt;">Yes</span><span style="font-size:12pt;">；否则输出一行</span><span style="font-size:12pt;">No</span><span style="font-size:12pt;">。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【样例输入】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> 2</span> 
</div>
<div>
<span style="font-size:12pt;"> 2</span> 
</div>
<div>
<span style="font-size:12pt;"> 0 0</span> 
</div>
<div>
<span style="font-size:12pt;"> 0 1</span> 
</div>
<div>
<span style="font-size:12pt;"> 3</span> 
</div>
<div>
<span style="font-size:12pt;"> 0 0 1</span> 
</div>
<div>
<span style="font-size:12pt;"> 0 1 0</span> 
</div>
<div>
<span style="font-size:12pt;"> 1 0 0</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【样例输出】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> No</span> 
</div>
<div>
<span style="font-size:12pt;"> Yes</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【数据规模】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于</span><span style="font-size:12pt;">20%</span><span style="font-size:12pt;">的数据，</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤ </span><span style="font-size:12pt;">7</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于</span><span style="font-size:12pt;">50%</span><span style="font-size:12pt;">的数据，</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤ </span><span style="font-size:12pt;">50</span> 
</div>
<p>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于</span><span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据，</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤ </span><span style="font-size:12pt;">200</span> 
</p>
