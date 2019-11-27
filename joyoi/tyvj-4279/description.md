# 

 
 # 题目背景 
<p>水题大法好</p> 

 
 # 题目描述 
<p>xzj学数学听说了一个SB算法，因此他现在想要知道经过多少次SB运算能够将一个数变成1，但是由于他懒得算了，所以只能靠机智的你了。每次SB运算是这样的：如果一个数为偶数，那么除二，否则，乘上一个数3再增加1。</p>

<p>但是xzj还有一个特殊要求：当运算中出现大于等于3*10<sup>6</sup>​的结果且输入的数不大于3*10<sup>6</sup>时输出-1，因为他在输入小于等于3*10<sup>6</sup>只能使用一个数据类型，而这个数据类型只能包含0~3*10<sup>6</sup>的数。但是如果输入更大，他会使用更先进的类型。</p> 

 
 # 输入格式 
<p>第一行包含一个数T，表示数据组数。</p>

<p>随后的T行，每行一个数N。</p> 

 
 # 输出格式 
<p>共T行，即SB运算次数。</p> 

 
 # 提示 
<p>对于其中30%的数据，T=1，1&le;N&le;1000。</p>

<p>对于其中20%的数据，5*10<sup>5</sup>&le;T&le;8*10<sup>5</sup>，1&le;N&le;1*10<sup>6。</sup></p>

<p>对于其余50%的数据，2&le;T&le;10<sup>5</sup>，1&le;N&le;2*10<sup>9</sup>。</p>

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
<tr><td>3
5
50
2999999</td><td>5
24
-1</td></tr></table>
