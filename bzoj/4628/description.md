
# Description

<div class="content"><div>路由表中每一项对应了一个形如 1011101?????????????????????????的规则，会匹配指定的前缀为给定形式的 ip</div>
<div>。 当有多个规则匹配时，前缀最长的生效。同一时刻不会有多个匹配的规则的前缀一样长。每一个时刻，会有一</div>
<div>条规则被加入，或者之前被加入的某条规则会过期。给一系列 ip，问每一个 ip 在一个给定的时间区间内匹配到</div>
<div>的生效规则变了几次？</div>
<div>例如，有一系列事件：</div>
<div>Add 110</div>
<div>Add 11</div>
<div>Del 110</div>
<div>Del 11</div>
<div>Add 110</div>
<div>那么,IP 地址 11011101001001010101011101000010在这五个时刻之后匹配到</div>
<div>的生效规则分别是：</div>
<div>110（第一条），</div>
<div>110（第一条），</div>
<div>11（第二条），</div>
<div>空，</div>
<div>110（第三条）。</div>
<div>其中，在第二个事件后到第五个事件后的这段过程中，一共变了3次。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个整数 N 和 Q，表示时刻的个数与查询的个数。</div>
<div>接下来 N 行，每行描述一个事件。事件的格式是</div>
<div>Add s 表示新建一个规则，匹配前缀为 s 的所有 ip.</div>
<div>Del s 表示把当前前缀 s 对应的规则删掉（过期）。保证之前有这样的一条规则还没被删。</div>
<div>接下来 Q 行，每行一个 ip 与两个整数 a,b，表示查询 ip 在第 a 个事件（从 1 开始数）</div>
<div>后到第 b 个事件后的这段时间里，这个 ip 匹配到的生效规则变化的次数。 ip 用01字符串来表示。</div>
<div>1 ≤ N, Q ≤ 10^5，串长不超过32</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对每个查询，输出所求的变化次数.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
Add 110<br/>
Add 11<br/>
Del 110<br/>
Del 11<br/>
Add 110<br/>
11011101001001010101011101000010 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

