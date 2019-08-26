
# Description

<div class="content"><div>小A最近一直在找自己的爸爸，用什么办法呢，就是DNA比对。小A有一套自己的DNA序列比较方法，其最终目标是最</div>
<div>大化两个DNA序列的相似程度，具体步骤如下：1.给出两个DNA序列，第一个长度为n，第二个长度为m。2.在两个序</div>
<div>列的任意位置插入任意多的空格，使得两个字符串长度相同3.逐位进行匹配，如果两个序列相同位置上的字符都不</div>
<div>是空格，假设第一个是x，第二个是y，那么他们的相似程度由d(x,y)定义。对于两个序列中任意一段极长的长度为</div>
<div>k的连续空格，我们定义这段空格的相似程度为g(k)=-A-B(k-1)。那么最终两个序列的相似程度就是所有的d(x,y)</div>
<div>加上所有的极长空格段的相似程度之和。现在小A通过某种奥妙重重的方式得到了小B的DNA序列中的一段，他想请</div>
<div>你帮他算一下小A的DNA序列和小B的DNA序列的最大相似程度。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>输入第1行一个字符串，表示小A的DNA序列。</div>
<div>输入第2行一个字符串，表示小B的DNA序列。</div>
<div>接下来4行，每行4个整数，用空格隔开，表示d数组，</div>
<div>具体顺序如下所示。</div>
<div>d(A,A)d(A,T)d(A,G)d(A,C)</div>
<div>d(T,A)d(T,T)d(T,G)d(T,C)</div>
<div>d(G,A)d(G,T)d(G,G)d(G,C)</div>
<div>d(C,A)d(C,T)d(C,G)d(C,C)</div>
<div>最后一行两个用空格隔开的正整数A,B，意义如题中所述。</div>
<div>对于所有测试点</div>
<div>有0&lt;B&lt;A≤1000,-1000≤d(x,y)≤1000,d(x,y)=d(y,x)，</div>
<div>序列只包含{A,T,G,C}四种字符。</div>
<div>N+M&lt;=3000</div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出共一行，表示两个序列的最大相似程度</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">ATGG<br/>
ATCC<br/>
5 -4 -4 -4<br/>
-4 5 -4 -4<br/>
-4 -4 5 -4<br/>
-4 -4 -4 5<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
首先，将序列补成如下形式（&#34;-&#34;代表空格）<br/>
ATGG--<br/>
AT--CC<br/>
然后所有d(x,y)的和为d(A,A)+d(T,T)=10所有极长连续空格段的相似程度之和为g(2)+g(2)=-6总和为4，可以验证<br/>
，这是相似程度最大的情况。</span></div>

# Hint

<div class="content"><p></p><div>来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</div><br/>
<div>Credit：idea/邢健开　命题/邢健开　验题/陈宇</div><br/>
<div>Git Repo：https://git.thusaac.org/publish/CodePlus201711</div><br/>
<div>本次比赛的官方网址：cp.thusaac.org</div><br/>
<div>感谢腾讯公司对此次比赛的支持。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

