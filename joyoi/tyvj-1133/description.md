# 

 
 # 题目背景 
在现代文明社会中，大家在诸如银行办理业务、车站买票等活动时都很文明<BR>没有插队的现象，本着“先来先服务”的规矩。<BR> 

 
 # 题目描述 
五一马上到了，凡凡的爸爸打算上银行去取点钱，带着一向表现很好的凡凡同学到海南旅游，凡凡的爸爸到银行时发现很多人在办理业务，凡凡的爸爸就自觉地在排队机上去了一个业务号码，并焦急的等待着银行柜台叫自己的号码...... 

 
 # 输入格式 
输入中包含I（表示等待办理业务）和顾客的序号；<BR>或者&nbsp;O（表示办理完业务的人离开）；<BR>输入数据不超过100行。<BR> 

 
 # 输出格式 
输出银行排队中出队顾客序列，若队列为空（没人等待），则输出“None” 

 
 # 提示 
由于本题中没有明确说明个数，所以输入时可用下面方式<BR>int&nbsp;x;<BR>char&nbsp;ch;<BR>while&nbsp;(cin&gt;&gt;ch)<BR>{<BR>&nbsp;&nbsp;&nbsp;&nbsp;If&nbsp;(ch=='I')<BR>&nbsp;&nbsp;&nbsp;&nbsp;{<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cin&gt;&gt;x;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;….<BR>&nbsp;&nbsp;&nbsp;&nbsp;}<BR>&nbsp;&nbsp;&nbsp;If&nbsp;(ch=='O')<BR>&nbsp;&nbsp;&nbsp;{<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;….<BR>&nbsp;&nbsp;&nbsp;}<BR>}<BR>栈和队列 
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
<tr><td>O
I 1
I 2
O 
I 3
O
O
O
</td><td>None
1
2
3
None
</td></tr></table>
