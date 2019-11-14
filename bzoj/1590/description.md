
# Description

<div class="content"><div><span style="font-size: medium">    贝茜正在领导奶牛们逃跑．为了联络，奶牛们互相发送秘密信息．</span></div>
<div><span style="font-size: medium">    信息是二进制的，共有M(1≤M≤50000)条．反间谍能力很强的约翰已经部分拦截了这些</span><span style="font-size: medium">信息，知道了第i条二进制信息的前bi(l《bi≤10000)位．他同时知道，奶牛使用N(1≤N≤</span><span style="font-size: medium">50000)条密码．但是，他仅仅了解第J条密码的前cj(1≤cj≤10000)位．</span></div>
<div><span style="font-size: medium">    对于每条密码J，他想知道有多少截得的信息能够和它匹配．也就是说，有多少信息和这条密码有着相同的前缀．当然，这个前缀长度必须等于密码和那条信息长度的较小者．</span></div>
<div><span style="font-size: medium">    在输入文件中，位的总数（即∑Bi+∑Ci）不会超过500000.</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入N和M，之后N行描述秘密信息，之后M行描述密码．每行先输入一个整数表示信息或密码的长度，之后输入这个信息或密码．所有数字之间都用空格隔开．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    共M行，输出每条密码的匹配信息数．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
3 0 1 0<br/>
1 1<br/>
3 1 0 0<br/>
3 1 1 0<br/>
1 0<br/>
1 1<br/>
2 0 1<br/>
5 0 1 0 0 1<br/>
2 1 1<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Four messages; five codewords.<br/>
The intercepted messages start with 010, 1, 100, and 110.<br/>
The possible codewords start with 0, 1, 01, 01001, and 11.<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
1<br/>
1<br/>
2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>0 matches only 010: 1 match 1 matches 1, 100, and 110: 3 matches 01 matches only 010: 1 match 01001 matches 010: 1 match 11 matches 1 and 110: 2 matches</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

