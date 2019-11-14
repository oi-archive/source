
# Description

<div class="content"><div>曾经发明了信号增幅仪的发明家SHTSC又公开了他的新发明：自动刷题机--一种可以自动AC题目的神秘装置。自动</div>
<div>刷题机刷题的方式非常简单：首先会瞬间得出题目的正确做法，然后开始写程序，每秒，自动刷题机的代码生成模</div>
<div>块会有两种可能的结果：</div>
<div>A.写了x行代码。</div>
<div>B.心情不好，删掉了之前写的y行代码。（如果y大于当前代码长度则相当于全部删除。）</div>
<div>对于每个OJ所有题目，存在某个固定的长度n&gt;0。一旦自动刷题机在某秒结束时积累了大于等于n行的代码，它就会</div>
<div>自动提交并AC此题，然后新建一个文件开始写下一题。SHTSC在某个OJ上跑了一天的自动刷题机，得到了很多条关</div>
<div>于写代码的日志信息。他突然发现自己没有记录这个OJ的n究竟是多少。所幸他通过自己在OJ上的Rank知道了机一</div>
<div>共切了k道题。希望你计算n可能的最小值和最大值。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数l，k，表示刷题机的日志一共有l行，一共了切了k题。</div>
<div>第二行l个整数，x1…xl。xi&gt;=0表示写了xi行代码。xi&lt;0表示删除了这道题的-xi行代码。</div>
<div>1&lt;=l,k&lt;=100000，|xi|&lt;=10^9</div>
<p></p></div>

# Output

<div class="content"><div>输出两个数a，b。分别代表n可能的最小值和最大值。如果不存在这样的n则输出-1。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
2<br/>
5<br/>
-3<br/>
9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 7<br/>
//样例1：如果n=2那么刷题机就会切掉3题。但如果n&gt;7刷题机最多只能切1题。考虑n=4发生了什么。<br/>
第一秒：刷题机写了2行。<br/>
第二秒：刷题机又写了5行，共有7行，提交，自信AC。<br/>
第三秒：刷题机删掉了3行，共有0行。<br/>
第四秒：刷题机写了9行，共有9行，提交，自信AC。<br/>
一共AC了两题。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

