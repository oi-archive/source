
# Description

<div class="content"><div>F在生日这天收到了一份特别的礼物一盒巧克力。</div>
<div>这盒巧克力有n颗，每颗巧克力有甜度si和苦度bi两种属性。</div>
<div>F和Q打算一起吃这盒巧克力，他们要轮流选择巧克力吃。但是因为一</div>
<div>些不可描述的原因，他们在选择巧克力时，只能选择甜度或者苦度是当前</div>
<div>两个人吃过的巧克力中最大的那些巧克力。具体来说，假设已经选择的巧</div>
<div>克力集合为s，接下来能选择的巧克力x需要满足下列条件的至少一个：</div>
<div>sx &gt; st, 存在t 属于 s</div>
<div>bx &gt; bt,存在t 属于 s</div>
<div>F让Q先选巧克力，Q想要自己吃到的巧克力比F多，F不想Q吃到的巧克力比自己多。</div>
<div>F想要知道如果他们都按照最优策略行动，Q能不能吃的比自己多？</div></div>

# Input

<div class="content"><div>第一行一个数t，表示数据组数。</div>
<div>每组数据格式如下：</div>
<div>第一行一个数N</div>
<div>接下来N行，每行两个整数si,bi</div>
<div>t ≤ 10, n ≤ 1e5, 0 &lt; si,bi ≤ 1e9</div></div>

# Output

<div class="content"><div>每组数据输出一行，&#39;YES&#39; 或者&#39;NO&#39;。表示Q能不能吃的比F多。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3<br/>
10 2<br/>
1 10<br/>
10 3<br/>
3<br/>
10 1<br/>
10 10<br/>
1 10<br/>
3<br/>
10 2<br/>
1 10<br/>
4 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">NO<br/>
YES<br/>
YES</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=匿名原创，本站版权所有">匿名原创，本站版权所有</a></p></div>

