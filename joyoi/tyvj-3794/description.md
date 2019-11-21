# 

 
 # 题目背景 
<p>小Q学习位运算时发现了异或的秘密。</p> 

 
 # 题目描述 
<p>小Q是一个热爱学习的人，他经常去维基百科（<a href="http://en.wikipedia.org/wiki/Main_Page">http://en.wikipedia.org/wiki/Main_Page</a>）学习计算机科学。</p>

<p>就在刚才，小Q认真地学习了一系列位运算符（<a href="http://en.wikipedia.org/wiki/Bitwise_operation">http://en.wikipedia.org/wiki/Bitwise_operation</a>），其中按位异或的运算符&nbsp;xor&nbsp;对他影响很大。按位异或的运算符是双目运算符。按位异或具有交换律，即i&nbsp;xor&nbsp;j&nbsp;=&nbsp;j&nbsp;xor&nbsp;i。</p>

<p>他发现，按位异或可以理解成被运算的数字的二进制位对应位如果相同，则结果的该位置为0，否则为1，例如1(01)&nbsp;xor&nbsp;2(10)&nbsp;=&nbsp;3(11)。</p>

<p>他还发现，按位异或可以理解成数字的每个二进制位进行了不进位的加法，例如3(11)&nbsp;xor&nbsp;3(11)&nbsp;=&nbsp;0(00)。</p>

<p>于是他想到了两个关于异或的问题，这两个问题基于一个给定的非负整数序列A<sub>1</sub>,&nbsp;A<sub>2</sub>,&nbsp;...,&nbsp;A<sub>n</sub>，其中n是该序列的长度。</p>

<p>第一个问题是，如果用f(i,&nbsp;j)表示A<sub>i</sub>&nbsp;xor&nbsp;A<sub>i+1</sub>&nbsp;xor&nbsp;...&nbsp;xor&nbsp;A<sub>j</sub>，则任意的1&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;j&nbsp;&lt;=&nbsp;n的f(i,&nbsp;j)相加是多少。</p>

<p>第二个问题是，如果用g(i,&nbsp;j)表示A<sub>i</sub>&nbsp;+&nbsp;A<sub>i+1</sub>&nbsp;+&nbsp;...&nbsp;+&nbsp;A<sub>j</sub>，则任意的1&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;j&nbsp;&lt;=&nbsp;n的g(i,&nbsp;j)异或在一起是多少。</p>

<p>比如说，对于序列{1,&nbsp;2}，所有的f是{1,&nbsp;2,&nbsp;1&nbsp;xor&nbsp;2}，加起来是6；所有的g是{1,&nbsp;2,&nbsp;1&nbsp;+&nbsp;2}，异或起来是0。</p>

<p>他觉得这两个问题都非常的有趣，所以他找到了你，希望你能快速解决这两个问题，其中第一个问题的答案可能很大，你只需要输出它对998244353（一个质数）取模的值即可。</p> 

 
 # 输入格式 
<p>第一行一个正整数n，表示序列的长度。</p>

<p>第二行n个非负整数A<sub>1</sub>,&nbsp;A<sub>2</sub>,&nbsp;...,&nbsp;A<sub>n</sub>，表示这个序列。</p> 

 
 # 输出格式 
<p>两个整数，表示两个问题的答案，空格隔开，其中第一个问题的答案要对998244353（一个质数）取模。</p> 

 
 # 提示 
<h4>数据范围</h4>

<p>前30%的数据满足n&nbsp;&lt;=&nbsp;500。</p>

<p>前50%的数据满足n&nbsp;&lt;=&nbsp;5000。</p>

<p>前70%的数据满足A<sub>1</sub>&nbsp;+&nbsp;A<sub>2</sub>&nbsp;+&nbsp;...&nbsp;+&nbsp;A<sub>n</sub>&nbsp;&lt;=&nbsp;10^6。</p>

<p>100%的数据满足n&nbsp;&lt;=&nbsp;10^5,&nbsp;A<sub>i</sub>&nbsp;&lt;=&nbsp;10^6。</p>

<h4>来源</h4>

<p>ftiasch，没有LaTex出题人不开心。</p> 
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
<tr><td>2
1 2
</td><td>6 0
</td></tr></table>
