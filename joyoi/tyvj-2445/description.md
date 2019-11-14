# 

 
 # 题目描述 
<p>
为了研究农场的气候,Betsy帮助农夫John做了N(1 <= N <= 100)次气压测量并按顺序记录<br>了结果M_1...M_N(1 <= M_i <= 1,000,000).<br>Betsy想找出一部分测量结果来总结整天的气压分布. 她想用K(1 <= K <= N)个数s_j<br>(1 <= s_1 < s_2 < ... < s_K <= N)来概括所有测量结果. 她想限制如下的误差:<br><br>对于任何测量结果子集,每一个非此子集中的结果都会产生误差.总误差是所有测量结果的误差之<br>和.更明确第说, 对于每一个和所有s_j都不同的i:<br><br>* 如果 i 小于 s_1, 误差是:<br>             2 * | M_i - M_(s_1) | <br><br>* 如果i在s_j和s_(j+1)之间,误差是:<br>            | 2 * M_i - Sum(s_j, s_(j+1)) |  <br>  注:Sum(x, y) = M_x + M_y; (M_x 和 M_y 之和)<br><br>* 如果i大于s_K,误差为:<br>             2 * | M_i - M_(s_K) |<br><br>Besty给了最大允许的误差E (1 <= E <= 1,000,000),找出最小的一部分结果史得误<br>差最多为E.<br><br></p> 

 
 # 输入格式 
<p>
* 第一行: 两个空格分离的数: N 和 E<br><br>* 第2..N+1行: 第i+1行包含一次测量记录:M_i<br><br></p> 

 
 # 输出格式 
<p>
* 第一行: 两个空格分开的数: 最少能达到误差小于等于E的测量数目和使用那个测量<br>数目能达到的最小误差.<br><br></p> 

 
 # 提示 
<p>
<br>选择第二和第四次测量结果能达到最小误差17. 第一次结果的误差是2*|10-3| = 14;<br>第三次结果的误差是|2*20 - (3+40)|=3.<br></p> 
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
<tr><td>4 20
10
3
20
40

输入解释:

Bessie做了4次记录,分别为10,3,20,和40.最大允许误差是20.
</td><td>2 17</td></tr></table>
