
# Description

<div class="content"><div>IOI国历史研究的第一人——JOI教授，最近获得了一份被认为是古代IOI国的住民写下的日记。JOI教授为了通过这份日记来研究古代IOI国的生活，开始着手调查日记中记载的事件。</div>
<div>日记中记录了连续N天发生的时间，大约每天发生一件。</div>
<div>事件有种类之分。第i天(1&lt;=i&lt;=N)发生的事件的种类用一个整数Xi表示，Xi越大，事件的规模就越大。</div>
<div>JOI教授决定用如下的方法分析这些日记：</div>
<div>1.<span class="Apple-tab-span" style="white-space:pre">	</span>选择日记中连续的一些天作为分析的时间段</div>
<div>2.<span class="Apple-tab-span" style="white-space:pre">	</span>事件种类t的重要度为t*(这段时间内重要度为t的事件数)</div>
<div>3.<span class="Apple-tab-span" style="white-space:pre">	</span>计算出所有事件种类的重要度，输出其中的最大值</div>
<div>现在你被要求制作一个帮助教授分析的程序，每次给出分析的区间，你需要输出重要度的最大值。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个空格分隔的整数N和Q，表示日记一共记录了N天，询问有Q次。</div>
<div>接下来一行N个空格分隔的整数X1...XN，Xi表示第i天发生的事件的种类</div>
<div>接下来Q行，第i行(1&lt;=i&lt;=Q)有两个空格分隔整数Ai和Bi，表示第i次询问的区间为[Ai,Bi]。</div>
<p></p></div>

# Output

<div class="content"><div>输出Q行，第i行(1&lt;=i&lt;=Q)一个整数，表示第i次询问的最大重要度</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
9 8 7 8 9<br/>
1 2<br/>
3 4<br/>
4 4<br/>
1 4<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
8<br/>
8<br/>
16<br/>
16</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=N&lt;=10^5</div><br/>
<div>1&lt;=Q&lt;=10^5</div><br/>
<div>1&lt;=Xi&lt;=10^9 (1&lt;=i&lt;=N)</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技1 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技1 By PoPoQQQ</a></p></div>

