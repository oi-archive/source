# 

 
 # 题目描述 
<p>
在一次军事行动中有一批空降兵要降落在沙漠中拆除炸弹. 空降兵按照预定的顺序跳伞并降落到指定的位置.一旦降落他们便呆在原地不动了. 

 
 # 输入格式 
<p>
第一行一个数n ( 2 <= n <= 2 000) – 空降兵的个数. 接下来n 行每行描述一个空降兵. 每个空降兵用三个整数: x, y 和 r ( -1000 <= x, y <= 1000, 1 <= r <= 5000). 表示空降兵在点(x, y) 着陆, 他的生存半径为 r. 

 
 # 输出格式 
<p>
输出一行表示最少需要派出多少空降兵.如果所有的空降兵都有可能牺牲的话输出NIE (NO in Polish). 
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
2 2 4
7 2 3
4 3 1
5 7 1
8 7 1
</td><td>4</td></tr></table>