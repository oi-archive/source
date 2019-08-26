
# Description

<div class="content"><div>osu 是一款群众喜闻乐见的休闲软件。 </div>
<div>我们可以把osu的规则简化与改编成以下的样子: </div>
<div>一共有n次操作，每次操作只有成功与失败之分，成功对应1，失败对应0，n次操作对应为1个长度为n的01串。在这个串中连续的 X个1可以贡献X^3 的分数，这x个1不能被其他连续的1所包含（也就是极长的一串1，具体见样例解释） </div>
<div>现在给出n，以及每个操作的成功率，请你输出期望分数，输出四舍五入后保留1位小数。 </div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行有一个正整数n,表示操作个数。接下去n行每行有一个[0,1]之间的实数，表示每个操作的成功率。 </div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>只有一个实数，表示答案。答案四舍五入后保留1位小数。 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
0.5 <br/>
0.5 <br/>
0.5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">6.0 <br/>
</span></div>

# Hint

<div class="content"><p></p><div>【样例说明】 </div><br/>
<div>000分数为0，001分数为1，010分数为1，100分数为1，101分数为2，110分数为8，011分数为8，111分数为27，总和为48，期望为48/8=6.0 </div><br/>
<div><span style="font-family: &#39;Times New Roman&#39;;">N&lt;=100000</span></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

