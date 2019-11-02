# 

 
 # 题目背景 
第二届『Citric杯』NOIP提高组模拟赛&nbsp;第三题<BR><BR> 

 
 # 题目描述 
Lemon觉得他需要一个复杂的密码来保证他的帐号的安全。他经过多日思考，决定使用一个长度为奇数的回文串来作为他的密码。<BR>但是这个回文串太长了，Lemon记不住，于是Lemon决定把它记在本子上。当然直接把密码明文记录实在太愚蠢了，于是Lemon决定在记录时加入一些无意义的字符以保证密码的安全。<BR>具体来说，假设Lemon的密码串是S，Lemon选择了一个不超过len(S)/2的正整数x，然后把S的前x个字符组成的字符串设为Left，把S的后x个字符组成的字符串设为Right，把S其余的字符组成的字符串设为Mid.<BR>Lemon实际记录在密码本上的内容是A+Left+B+Mid+C+Right.&nbsp;其中A，B，C都是无意义的字符串（有可能是空串）。他觉得这样就很安全了。<BR><BR>某一天，Melon无意发现了Lemon的笔记本，并发现了这个字符串。Melon决定把Lemon的密码破解出来。但是显然有不计其数的可能密码。<BR>Melon认为，Lemon的密码一定很长，于是他想知道，这个字符串里隐藏的最长可能的密码有多长呢？<BR><BR> 

 
 # 输入格式 
输入数据第一行包含一个正整数N，表示字符串的长度。<BR>数据数据第二行包含一个长度为N的字符串，仅由小写字母组成，表示需要破译的字符串。<BR><BR> 

 
 # 输出格式 
输出数据仅包含一个整数，表示最长可能的密码的长度。<BR><BR> 

 
 # 提示 
最长的可能的密码是abcdefgfedcba，长度为13<BR>Lemon选择的x=4<BR>Left="abcd"&nbsp;Right="dcba"&nbsp;Mid="efgfe"<BR>A="orz"&nbsp;B="xyz"&nbsp;C="qwerty"<BR><BR> 
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
<tr><td>25
orzabcdxyzefgfeqwertydcba
</td><td>13

</td></tr></table>
