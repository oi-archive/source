# 

 
 # 题目描述 
<p>
A-B Problem(aminusb)<br><br>【题目描述】<br>　　给出一个A/B-C/D表示的分数减法算式，A，B，C，D均为不超过32767的正整数，求A/B-C/D的差，若差为整数，则输出这个整数；若差为分数，则按A/B格式输出；要求为最简分数，若差为负数，则在上述要求下最前面添加负号。<br>输入中A/B或C/D有可能不是最简分数，但是你的输出必须是最简分数。<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件aminusb.in的第1行为一个正整数T，表示数据组数，<br>　　接下来T行，每行为按A/B-C/D格式给出的算式。 <br><br></p> 

 
 # 输出格式 
<p>
　　输出文件aminusb.out包括T行，分别对于每个算式给出答案。<br><br></p> 

 
 # 提示 
<p>
【数据规模】<br>　　对于30%的数据，有T≤10；<br>　　对于100%的数据，有T≤50000。<br></p> 
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
<tr><td>3
1/3-1/2
10/4-2/2
3/2-1/2

</td><td>-1/6
3/2
1
</td></tr></table>
