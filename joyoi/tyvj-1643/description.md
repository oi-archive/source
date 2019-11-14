# 

 
 # 题目背景 
目睹Zj神犇的气场覆盖若干MM并使之为其倾心后，奶牛Hyc感到了莫大的压力，因为他自己是单身……趁着校庆愉快的气氛，奶牛Hyc决定向爱慕已久的MM-Zxl表白。经过N久的酝酿后，奶牛Hyc发现一个问题，表白里不可避免的出现了数字，比如&nbsp;爱你xx年，可是…… 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Zxl非常喜欢数字8和3，因此，所有有8和3组成的数字，Zxl都认为是幸运的，比如8833,3,888，但88733就不是幸运数了，因为Zxl不喜欢7，她只喜欢8和3。Zxl看到类似88733这样的非幸运数字就会很不开心，这次表白也就失败了。为了让表白尽可能成功，奶牛Hyc决定把一些不幸运的数写成一些幸运数的和。当然为了不把事情搞的麻烦，拆分的个数越少越好，个数相同时字典序越小越好。可是奶牛实力太差，只好请你帮忙。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;概括：给定一个表白中出现的数N，将其分解为一些幸运数的和，要求所用数字最少，如果有多组解要求字典序最小。无解则输出No&nbsp;solution<BR>对于字典序的解释<BR>对于数列a[1..n]&nbsp;&lt;&gt;&nbsp;b[1..n]&nbsp;我们寻找第一位子i&nbsp;使得a[i]&lt;&gt;b[i]&nbsp;，如果a[i]&nbsp;&lt;&nbsp;b[i]&nbsp;则a&nbsp;字典序小，&nbsp;否则b[i]&nbsp;字典序小 

 
 # 输入格式 
一行，一个整数N 

 
 # 输出格式 
一行，N&nbsp;的幸运分解，两个数之间用空格隔开。 

 
 # 提示 
对于20%的数据，n&lt;=100<BR>对于50%的数据，n&lt;=100000<BR>对于100%的数据，n&lt;=1000000000 
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
<tr><td>11
</td><td>3 8</td></tr></table>
