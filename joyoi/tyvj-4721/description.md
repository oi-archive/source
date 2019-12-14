# 

 
 # 题目描述 
<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">Bessie对最近她在农场中搞的恶作剧感到后悔，她决定帮助农夫John运送干草堆。</span></div>

<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">她开始面对的是N(1&lt;=N&lt;=1,000,000,N是奇数）个标记为1..N的空栈。农夫FJ给她一个指令序列，指令序列有</span></div>

<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">K(1&lt;=K&lt;=25,000)条指令，每个指令格式为&quot;A&nbsp;B&quot;，意味着Bessie需要为标号为A到B的所有栈栈顶放一个干草堆</span></div>

<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">举例说明，如果指令为&quot;10&nbsp;13&quot;，那么Bessie应该为栈10，11，12和13栈顶各加一个干草堆。</span></div>

<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">当Bessie按照指令序列完成搬运后，农夫FJ想知道N个栈中干草堆数目位于中间的那个数值（即把N个干草堆数排序中，中间的那个数值）</span></div>

<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">因为N是奇数，所以答案唯一。请输出这个数</span></div> 

 
 # 输入格式 
<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">第一行：两个数N和K</span></div>

<div style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;"><span style="font-size: medium;">第2..1+K行：每行两个数，描述了农夫的指令A&nbsp;B(1&lt;=A&lt;=&lt;=N)</span></div> 

 
 # 输出格式 
<p><span style="font-family: 'Times New Roman'; font-size: 14px; line-height: 24px; background-color: rgb(228, 240, 248);">一个数，N个干草堆数的中间数。</span></p> 
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
<tr><td>7 4
5 5
2 4
4 6
3 5</td><td>1</td></tr></table>
