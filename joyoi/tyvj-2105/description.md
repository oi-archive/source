# 

 
 # 题目背景 
<p>小明对英语一窍不通，令老师十分头疼。于是期末考试前夕，为了班级的及格率，小明被逼着开始背单词&hellip;&hellip;</p> 

 
 # 题目描述 
<p>老师给了小明一篇长度为N的英语文章，然后让小明背M个单词。为了确保小明不会在背单词时睡着，老师会向他提Q个问题，每次老师选择一个区间L..R，小明要回答在这段文字中他背过的单词总共出现过多少次。</p> 

 
 # 输入格式 
<p>第一行两个整数M、Q如前所述。第二行为英语文章。接下来M行每行一个需要背的单词。接下来Q行每行一个询问，包含两个整数L、R（含端点），即给定的文字区间。</p> 

 
 # 输出格式 
<p>Q行，对每个询问输出一行表示答案。</p> 

 
 # 提示 
<p>数据范围：<br />
对于30%的数据，1&lt;=N&lt;=10^3,1&lt;=Q&lt;=10^3<br />
对于60%的数据，1&lt;=N&lt;=10^5,1&lt;=Q&lt;=10^5<br />
对于100%的数据，1&lt;=N&lt;=5*10^5,1&lt;=M&lt;=10,1&lt;=Q&lt;=5*10^5,1&lt;=每个单词的长度&lt;=N,1&lt;=L&lt;=R&lt;=N<br />
提示：数据较大，请大家尽量采取高效率的读入输出方法。</p> 
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
<tr><td>3 3
ababaca
c
ba
aba
1 3
3 4
1 7
</td><td>2
0
5
</td></tr></table>
