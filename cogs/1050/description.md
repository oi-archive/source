# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目背景】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二届『Citric杯』NOIP提高组模拟赛 第三题</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon觉得他需要一个复杂的密码来保证他的帐号的安全。他经过多日思考，决定使用一个长度为奇数的回文串来作为他的密码。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">但是这个回文串太长了，Lemon记不住，于是Lemon决定把它记在本子上。当然直接把密码明文记录实在太愚蠢了，于是Lemon决定在记录时加入一些无意义的字符以保证密码的安全。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">具体来说，假设Lemon的密码串是S，Lemon选择了一个不超过len(S)/2的正整数x，然后把S的前x个字符组成的字符串设为Left，把S的后x个字符组成的字符串设为Right，把S其余的字符组成的字符串设为Mid.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon实际记录在密码本上的内容是A+Left+B+Mid+C+Right. 其中A，B，C都是无意义的字符串（有可能是空串）。他觉得这样就很安全了。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">某一天，Melon无意发现了Lemon的笔记本，并发现了这个字符串。Melon决定把Lemon的密码破解出来。但是显然有不计其数的可能密码。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Melon认为，Lemon的密码一定很长，于是他想知道，这个字符串里隐藏的最长可能的密码有多长呢？</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入数据第一行包含一个正整数N，表示字符串的长度。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据数据第二行包含一个长度为N的字符串，仅由小写字母组成，表示需要破译的字符串。</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出数据仅包含一个整数，表示最长可能的密码的长度。</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入文件样例】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">25</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">orzabcdxyzefgfeqwertydcba</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出文件样例】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">13</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">最长的可能的密码是abcdefgfedcba，长度为13</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon选择的x=4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Left=&#34;abcd&#34; Right=&#34;dcba&#34; Mid=&#34;efgfe&#34;</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">A=&#34;orz&#34; B=&#34;xyz&#34; C=&#34;qwerty&#34;</span><br/>
<br/>
<br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模约定】</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">时间限制1s</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于20%的数据，满足N&lt;=20</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于40%的数据，满足N&lt;=300</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于60%的数据，满足N&lt;=2000</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据，满足N&lt;=100000</span><br/>
<br/>
<br/>
