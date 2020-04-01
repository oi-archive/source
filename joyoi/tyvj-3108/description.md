# 

 
 # 题目背景 
<p>在html代码中，我们可以为元素设置style属性，在style中可以添加颜色、背景、字体大小等外观。</p> 

 
 # 题目描述 
<p>我们的Code&nbsp;Comb对于不同的评测结果，给出了不同的颜色，它具体的对应关系如下：</p>

<table border="1" cellpadding="1" cellspacing="1" style="width: 500px;">
	<tbody>
		<tr>
			<td>代码</td>
			<td>状态</td>
			<td>style</td>
		</tr>
		<tr>
			<td>0</td>
			<td>Accepted</td>
			<td>color:&nbsp;rgb(36,193,0);</td>
		</tr>
		<tr>
			<td>1</td>
			<td>Presentaition&nbsp;Error</td>
			<td><span style="line-height: 20.7999992370605px;">color:&nbsp;rgb(240,137,90);</span></td>
		</tr>
		<tr>
			<td>2</td>
			<td>Wrong&nbsp;Answer</td>
			<td><span style="line-height: 20.7999992370605px;">color:&nbsp;rgb(255,81,81);</span></td>
		</tr>
		<tr>
			<td>3</td>
			<td>Time&nbsp;Limit&nbsp;Exceeded</td>
			<td><span style="line-height: 20.7999992370605px;">color:&nbsp;rgb(148,0,224);</span></td>
		</tr>
		<tr>
			<td>4</td>
			<td>Memory&nbsp;Limit&nbsp;Exceeded</td>
			<td><span style="line-height: 20.7999992370605px;">color:&nbsp;rgb(148,0,224);</span></td>
		</tr>
	</tbody>
</table>

<p>现在有若干个评测状态，您需要根据状态给出html的style。</p> 

 
 # 输入格式 
<p>输入内容有若干行，因此请您在读入时判断是否读到EOF，每行是一个整数num表示状态的代码，0&le;num&le;4。</p> 

 
 # 输出格式 
<p>对于每个状态码输出一行为style值。</p> 
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
<tr><td>0
1</td><td>color: rgb(36,193,0);
color: rgb(240,137,90);</td></tr></table>
