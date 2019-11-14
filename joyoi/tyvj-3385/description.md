# 

 
 # 题目描述 
<p>
骨牌矩阵（gupai.pas\c\cpp）<br><br>【题目描述】<br>　　多米诺骨牌是一个小正方形方块，每个骨牌都标有一个数字（0至6），现在有28组骨牌，每组两个，各组编号为1至28，每组编号对应的两个骨牌数值如下：<br><br><center><img src="/source/joyoi/tyvj-3385/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM4NS9wcm9ibGVtc19pbWFnZXMvMjE3NC8xLmpwZw==.jpg"></img></center><br>现将这28组骨牌排成一个7 X 8矩阵，此时只能看到每个骨牌上的数字（0至6），而不能知道每组的组号。如左下图所示。请编程将每组骨牌分辨出来（见右下图，图中数字为对应左图每组骨牌的编号）。骨牌摆放可旋转，例如第9组骨牌经旋转可得如下4种放法：<br><br><img src="/source/joyoi/tyvj-3385/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM4NS9wcm9ibGVtc19pbWFnZXMvMjE3NC8yLmpwZw==.jpg"></img><br><br><center><img src="/source/joyoi/tyvj-3385/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM4NS9wcm9ibGVtc19pbWFnZXMvMjE3NC8zLmpwZw==.jpg"></img></center><br></p> 

 
 # 输入格式 
<p>
　　输入文件gupai.in包含了一个7 行 8列的骨牌矩阵，每行有8个0至6的整数，每个整数之间用空格分开，每行的行首、行末无多余空格。</p> 

 
 # 输出格式 
<p>
　　输出文件gupai.out，若问题无解，则输出“-1”；若有解，则将所有可能的解输出，每个解之间用一个空行分开，最后输出的解的总数，数字间用空格分开。<br></p> 
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
<tr><td>5 4 3 6 5 3 4 6
0 6 0 1 2 3 1 1
3 2 6 5 0 4 2 0
5 3 6 2 3 2 0 6
4 0 4 1 0 0 4 1
5 2 2 4 4 1 6 5
5 5 3 6 1 2 3 1
</td><td>6  20 20 27 27 19 25 25
6  18 2  2  3  19 8  8
21 18 28 17 3  16 16 7
21 4  28 17 15 15 5  7
24 4  11 11 1  1  5  12
24 14 14 23 23 13 13 12
26 26 22 22 9  9  10 10

1</td></tr></table>
