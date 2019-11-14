# 

 
 # 题目描述 
<p><img alt="" src="/source/joyoi/tyvj-2144/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjE0NC9odHRwOi8vY2V4b3UuaW1nNDgud2FsOC5jb20vaW1nNDgvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjMxMTkwOTMxLnBuZw==.png" style="width: 727px; height: 694px;" /></p> 

 
 # 输入格式 
<p>输入文件的第一行包含两个整数&nbsp;n&nbsp;和&nbsp;q，表示字符串和附加任务的数量，中间用一个空格隔开。&nbsp;</p>

<p>接下来&nbsp;n&nbsp;行，描述字符串，其中第&nbsp;i&nbsp;行包含一个字符串&nbsp;Si。&nbsp;</p>

<p>接下来&nbsp;q&nbsp;行，描述附加任务，其中第&nbsp;i&nbsp;行包含两个整数&nbsp;Xi&nbsp;和&nbsp;Yi，中间用一个空格隔开。&nbsp;</p> 

 
 # 输出格式 
<p>输出文件包含两行.</p>

<p>第一行包含一个非负整数&nbsp;W(P<sub>G</sub><sup>*</sup><span style="line-height: 20.8px;">)。</span></p>

<p>第二行包含&nbsp;n&nbsp;个用一个空格隔开的正整数，表示一个&nbsp;1&nbsp;到&nbsp;n&nbsp;的排列P<sub>B</sub><sup>*</sup>。</p>

<p>&nbsp;</p> 

 
 # 提示 
<h3>评分标准</h3>

<p>对于一个测试点：&nbsp;</p>

<p>如果输出文件的第一行正确可以得到&nbsp;2&nbsp;分；&nbsp;</p>

<p>如果输出文件的第二行正确可以得到&nbsp;8&nbsp;分；&nbsp;</p>

<p>如果输出文件的两行都正确则可以得到&nbsp;10&nbsp;分。&nbsp;</p>

<p>对于第二问中的排列，如果存在多个解，则输出任意一个解均可得分。&nbsp;</p>

<h3>数据范围</h3>

<p>对于&nbsp;10%的数据，n&nbsp;&le;&nbsp;10，q&nbsp;=&nbsp;1，&nbsp;每个字符串的长度不超过&nbsp;50；&nbsp;</p>

<p>对于&nbsp;20%的数据，n&nbsp;&le;&nbsp;50，q&nbsp;=&nbsp;1，&nbsp;每个字符串的长度不超过&nbsp;50；&nbsp;</p>

<p>对于&nbsp;50%的数据，n&nbsp;&le;&nbsp;1000，q&nbsp;&le;&nbsp;1000，&nbsp;每个字符串的长度不超过&nbsp;1000；&nbsp;</p>

<p>对于&nbsp;70%的数据，任意字符串不为其他任何一个字符串的前缀；</p>

<p>对于&nbsp;100%的数据，n&nbsp;&le;&nbsp;40&nbsp;000，q&nbsp;&le;&nbsp;100&nbsp;000，&nbsp;每个字符串的长度不超过&nbsp;10&nbsp;000；&nbsp;</p>

<p>对于&nbsp;100%的数据，所有字符串的长度和不超过&nbsp;200000。&nbsp;</p>

<h3>Tips</h3>

<p>10%数据：暴力枚举排列</p>

<p>20%数据：任务唯一，一定可满足，直接输出</p>

<p>50%数据：暴力维护限制即可.复杂度O(QMaxLength)即可通过</p>

<p>70%数据：不需要处理对应点非叶子的情况</p>

<p>&nbsp;</p> 
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
<tr><td>4 6
a
b
abc
bc
1 2
1 3
3 1
4 2
2 4
2 4
</td><td>2
3 1 2 4</td></tr></table>
