
# Description

<div class="content"><div>所谓的考试，就一定会有一道基本题给大家送分，而不嵌套题目的基本题怎么称得上基本呢？我们可以把基本题具</div>
<div>体看成由(),!四种字符组成的一个字符串，一道基本题是由若干个嵌套题中间加上,分隔组成，而所谓的嵌套题指</div>
<div>的是一对括号之间放入若干道由!分隔的基本题。例如(()!(()!())),(()!())就是一道基本题。当然在出题的时候</div>
<div>我们会尽量避免出到重题，嵌套题A和B相同指的是A中的所有基本题变换顺序之后可以变成B，例如(()!(()))与(((</div>
<div>))!())相同，而基本题A和B相同指的是将A的嵌套题平移后可以变成B，例如(),(()),(()!())与 (()),(()!()),()</div>
<div>还有 (()!()),(),(())相同，与(()),(),(()!())不同。这天小火车找到了n个合适的题目来出基本题，他想知道有</div>
<div>多少道恰有n对括号的合法且互不相同的基本题。</div>
<div>例如当n=3时共有5个不同的基本题，分别是&#34;((()))&#34; &#34;(()!())&#34;&#34;((),())&#34;&#34;(()),()&#34;和&#34;(),(),()&#34;。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数t和p，其中t表示数据组数。保证p为质数。</div>
<div>接下来t行每行一个整数n表示一组询问。</div>
<div>n&lt;=250&lt;p&lt;230,t&lt;=250</div>
<p></p></div>

# Output

<div class="content"><div>t行每行一个整数表示答案，对p取模。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2333<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
5<br/>
14<br/>
42</span></div>

# Hint

<div class="content"><p></p><p>三个测试点!</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Newnode原创，本站版权所有">Newnode原创，本站版权所有</a></p></div>

