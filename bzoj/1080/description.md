
# Description

<div class="content"><p>　　一个编码方案把每个字符对应到一个01串。例如{1,1010,01,10101}就是一个编码方案，它把四个字符（假设<br/>
它们为a,b,c,d）分别对应到串1、1010，01，10101。字符串的编码为各字符编码的连接。例如，在刚才的编码方<br/>
案中，字符串cac的编码为01101，dcb的编码为10101011010。 进一步分析发现，刚才的编码是相当劣质的，因为<br/>
字符串ba, acc和d的编码都是10101。对于一个编码方案，你的任务是找出三个不同的字符串，使得它们的编码全<br/>
相同。换句话说，找一个01编码串，使得它至少有三种解码方式。如果有多组解，这个编码串应当尽量短。</p></div>

# Input

<div class="content"><p>　　第一行包含一个整数n，即符号的个数。以下n行每行为一个长度不超过50的01串（可能为空串），即各符号的<br/>
编码。</p></div>

# Output

<div class="content"><p>　　仅一行，包含一个整数，即最短编码的长度。如果无解，输出-1。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1<br/>
1010<br/>
01<br/>
10101<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>　　2 &lt;= n &lt;= 30</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

