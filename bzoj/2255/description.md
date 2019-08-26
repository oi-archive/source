
# Description

<div class="content"><p>给你一个由A，G，T,C组成的字符串，其实就是基因串.<br/>
大家知道基因串是AGTCAGTCAGTC这样的形式。现在对这个<br/>
字符串进行位置编号，从0开始，到N-1，N代表整个字符串<br/>
的长度。现在给出T个要求，希望你对给出的字符串进行一些<br/>
变动，变动的方式有三种<br/>
1:设置某个位置的字符不可变<br/>
2:将某个位置的字符上升一个，例如从C变成A<br/>
3：将某个位置的字符下降一个，例如T变成G<br/>
注意两个相邻位置的字符不能同时发生变动<br/>
对于这T个要求，它们分别会给出一些位置，要求从这些位置取出来的<br/>
字符形成一个回文串。<br/>
</p></div>

# Input

<div class="content"><p>第一行给出N，T （1&lt;=N&lt;=100000,1&lt;=T&lt;=6000)<br/>
接下来有T行，每行先给出一个长度L，再给出L个数字其值在[0,N-1]</p></div>

# Output

<div class="content"><p>输出&#34;YES&#34;或者&#34;NO&#34;</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
AGTAT<br/>
2:1 4<br/>
2:0 1<br/>
3:0 2 4<br/>
<br/>
5 3<br/>
CATGC<br/>
0:<br/>
2:0 3<br/>
2:3 4<br/>
<br/>
00</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
NO</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

