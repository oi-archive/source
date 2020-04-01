
# Description

<div class="content"><div><span style="font-size: medium">CATS(Counter and Two Stacks)是一门有一个counter和两个栈的语言。S1和S2是两个栈，初始时候每个栈中有无数个0，压栈和出栈的操作分别为“PUSH”和“POP”。“ADD”取出栈顶两个元素，并把和重新压栈。下程序中T1，T2分别表示S1，S2的栈顶元素。</span></div>
<div align="left"><span style="font-size: medium">COUNTER = X</span></div>
<div align="left"><span style="font-size: medium">WHILE COUNTER &gt; 0</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">S2 PUSH T1                      //把S1栈顶元素压入S2</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">S1 POP                             //S1栈顶元素出栈</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">FLIP LAST BINARY BIT OF ALL NUMBERS IN S1 //把S1中所有数的最后一位取反</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">IF T2 &gt; L</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">COUNTER = COUNTER - 1</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">IF COUNTER == 0 PRINT T2</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">ELSE</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S2 PUSH N</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S2 PUSH N</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S2 ADD</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S2 ADD</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S1 PUSH T2</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S1 PUSH T2</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt" align="left"><span style="font-size: medium">S2 POP</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt"><span style="font-size: medium">S2 POP</span></div>
<div><span style="font-size: medium">求该程序对于给定输入X,L,N的输出。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行一个整数Q，接下来Q行每行有三个正整数分别为X,L和N，其中L不是N的倍数。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出共Q行，每行一个整数，为题目程序对于每组X,L和N的输出。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4 5 2<br/>
18 6 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
9<br/>
样例输入输出解释：.<br/>
对于第一组X,L和N，以下为程序循环时栈S1和COUNTER的数值。为了表示方便，只显示栈S1最顶端的4个元素。每行最左边的数为S1的栈顶元素。<br/>
COUNTER: 4<br/>
S1: 0000...<br/>
COUNTER: 4<br/>
S1: 4411...<br/>
COUNTER: 4<br/>
S1: 8850...<br/>
COUNTER: 3<br/>
S1: 9411...<br/>
COUNTER: 2<br/>
S1: 5000...<br/>
COUNTER: 2<br/>
S1: 9911...<br/>
COUNTER: 1<br/>
S1: 8000...<br/>
在下个循环中，COUNTER= 0 所以输出为8。</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
 <br/><br/>
数据规模：OJ中只有一组数据，Q=223100，X,N,L&lt;=2^60-1。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Hta">By Hta</a></p></div>

