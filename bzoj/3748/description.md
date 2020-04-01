
# Description

<div class="content"><div>考虑将正整数n拆分成几个不同的平方数之和，比如30=1^2 + 2^2 + 5^2=1^2 + 2^2 + 3^2 + 4^2，而8不存在这样的拆分。</div>
<div>用k(n)表示n的拆分中，最大的底数最小可能是多少。如果n不存在这样的拆分，则令k(n)=∞。例如，k(1)=1,k(8)=∞,k(378)=12,k(380)=10。</div>
<div>定义一个数x被称为“超重”的，当且仅当存在y&gt;x，使得k(y)&lt;k(x)。从上面的例子可知，378是一个“超重”的数。</div>
<div>给定n，你需要：</div>
<div>(1)求出k(n)</div>
<div>(2)求出1~n中有几个“超重”的数。</div>
<p></p></div>

# Input

<div class="content"><div>输入仅一行，包含一个正整数n(1&lt;=n&lt;=10^18)。</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出一行包含两个整数，分别为对上述两个问题的答案。如果k(n)=∞，则输出一个减号&#39;-&#39;代替。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
30<br/>
<br/>
<br/>
样例输入2：<br/>
8</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1：<br/>
4 15<br/>
<br/>
样例输出2：<br/>
- 5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

