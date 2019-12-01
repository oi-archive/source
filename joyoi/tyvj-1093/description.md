# 

 
 # 题目背景 
XX学校风靡一款智力游戏，也就是数独（九宫格），先给你一个数独，并需要你验证是否符合规则。 

 
 # 题目描述 
具体规则如下:<BR>每一行都用到1,2,3,4,5,6,7,8,9，位置不限，<BR>每一列都用到1,2,3,4,5,6,7,8,9，位置不限，<BR>每3×3的格子（共九个这样的格子）都用到1,2,3,4,5,6,7,8,9，位置不限，<BR>游戏的过程就是用1,2,3,4,5,6,7,8,9填充空白，并要求满足每行、每列、每个九宫格都用到1,2,3,4,5,6,7,8,9。<BR>如下是一个正确的数独:<BR>5&nbsp;8&nbsp;1&nbsp;4&nbsp;9&nbsp;3&nbsp;7&nbsp;6&nbsp;2<BR>9&nbsp;6&nbsp;3&nbsp;7&nbsp;1&nbsp;2&nbsp;5&nbsp;8&nbsp;4<BR>2&nbsp;7&nbsp;4&nbsp;8&nbsp;6&nbsp;5&nbsp;9&nbsp;3&nbsp;1<BR>1&nbsp;2&nbsp;9&nbsp;5&nbsp;4&nbsp;6&nbsp;3&nbsp;7&nbsp;8<BR>4&nbsp;3&nbsp;6&nbsp;1&nbsp;8&nbsp;7&nbsp;2&nbsp;9&nbsp;5<BR>7&nbsp;5&nbsp;8&nbsp;3&nbsp;2&nbsp;9&nbsp;1&nbsp;4&nbsp;6<BR>8&nbsp;9&nbsp;2&nbsp;6&nbsp;7&nbsp;1&nbsp;4&nbsp;5&nbsp;3<BR>6&nbsp;1&nbsp;5&nbsp;9&nbsp;3&nbsp;4&nbsp;8&nbsp;2&nbsp;7<BR>3&nbsp;4&nbsp;7&nbsp;2&nbsp;5&nbsp;8&nbsp;6&nbsp;1&nbsp;9<BR><BR><BR> 

 
 # 输入格式 
输入n个数独，你来验证它是否违反规则.<BR>第一行为数独个数，第二行开始为第一个数独，之后为第二个，至第n个.<BR>注意！每个数独之间有一个回车隔开!<BR> 

 
 # 输出格式 
若正确则输出”Right”若不正确则输出”Wrong”&nbsp;输出一个换一行<BR> 

 
 # 提示 
1&lt;=n&lt;=20&nbsp;（输入的数独个数）<BR>不论输入的数独是错误的还是正确的,数据都保证每个数在1-9之间,即只会出现因为有相同的数而导致违反规则,而不会因为数字超出了1-9的范围而违反规则.<BR><BR>Vivian&nbsp;Snow 
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
<tr><td>2
5 8 1 4 9 3 7 6 2
9 6 3 7 1 2 5 8 4
2 7 4 8 6 5 9 3 1
1 2 9 5 4 6 3 7 8
4 3 6 1 8 7 2 9 5
7 5 8 3 2 9 1 4 6
8 9 2 6 7 1 4 5 3
6 1 5 9 3 4 8 2 7
3 4 7 2 5 8 6 1 9

1 2 3 4 5 6 7 8 9
2 3 4 5 6 7 8 9 1
3 4 5 6 7 8 9 1 2
4 5 6 7 8 9 1 2 3
5 6 7 8 9 1 2 3 4
6 7 8 9 1 2 3 4 5
7 8 9 1 2 3 4 5 6
8 9 1 2 3 4 5 6 7
9 1 2 3 4 5 6 7 8
</td><td>Right
Wrong</td></tr></table>
