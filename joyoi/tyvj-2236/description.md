# 

 
 # 题目描述 
<p>
给定某个字符串,长度为N,它只由"I"和"X"组成.并且有不超过K对"I"与"X"是相邻的.<br>例如对于字符串"IXXIIXXX",它就是XI-8-3,即长度为8,"I"与"X"相邻的对数不超过3.<br>当然你要说它是XI-8-4也行,甚至于XI-8-K(K>=3).值得注意的是:由于字符串的首尾不<br>固定,"IXXIIXXX"也可以看成"XXXIIXXI",但由于每个字符串只有一个序号,因而我们对<br>这种由于颠倒首尾所产生的字符串,取两者之中字典序较小的那个为基准,当然如果一个<br>字符串它是回文串的话,那就无所谓了.<br>现在给定N,K的值,我们可以找到许多满足条件的字符串,现在希望能找出排在第i个的是<br>哪个字符串,例如N=3,K=2,i=5时,我们可以按字典序找出如下的字符串:"III", "IIX", "IXI",<br>"IXX", "XIX","XXX".那么排在第5个位置的为"XIX"<br></p> 

 
 # 输入格式 
<p>
每行给定N,K,i,含义如上所述<br>规定:0<=K<N<=60,0<i<10^18<br></p> 

 
 # 输出格式 
<p>
希望你能找出相应的字符串,如果找不出来就输出"NO SUCH STONE"<br><br>input data1:<br>3 2 5<br><br>input data2:<br>3 2 7<br><br></p> 

 
 # 提示 
<p>
0 <= k < n<= 60<br> 0 < i < 10^18</p> 
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
<tr><td>output data1:
XIX

output data2:
NO SUCH STONE</td><td></td></tr></table>
