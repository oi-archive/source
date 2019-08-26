
# Description

<div class="content"><p> 印尼首都雅加达市有 N 座摩天楼，它们排列成一条直线，我们从左到右依次将它们编号为 0 到 N−1。除了这 N 座摩天楼外，雅加达市没有其他摩天楼。</p>
<div></div>
<div>有 M 只叫做 “doge” 的神秘生物在雅加达市居住，它们的编号依次是 0 到 M−1。编号为 i 的 doge 最初居住于编号为 Bi 的摩天楼。每只 doge 都有一种神秘的力量，使它们能够在摩天楼之间跳跃，编号为 i 的 doge 的跳跃能力为 Pi （Pi&gt;0）。</div>
<div></div>
<div>在一次跳跃中，位于摩天楼 b 而跳跃能力为 p 的 doge 可以跳跃到编号为 b−p （如果 0≤b−p&lt;N）或 b+p （如果 0≤b+p&lt;N）的摩天楼。</div>
<div></div>
<div>编号为 0 的 doge 是所有 doge 的首领，它有一条紧急的消息要尽快传送给编 号为 1 的 doge。任何一个收到消息的 doge 有以下两个选择:</div>
<div></div>
<div>跳跃到其他摩天楼上；</div>
<div>将消息传递给它当前所在的摩天楼上的其他 doge。</div>
<div>请帮助 doge 们计算将消息从 0 号 doge 传递到 1 号 doge 所需要的最少总跳跃步数，或者告诉它们消息永远不可能传递到 1 号 doge。</div>
<div></div></div>

# Input

<div class="content"><p>输入的第一行包含两个整数 N 和 M。</p>
<div>
<div></div>
<div>接下来 M 行，每行包含两个整数 Bi 和 Pi。</div>
<div></div>
</div></div>

# Output

<div class="content"><p>输出一行，表示所需要的最少步数。如果消息永远无法传递到 1 号 doge，输出 −1。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
0 2<br/>
1 1<br/>
4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
explanation<br/>
下面是一种步数为 5 的解决方案：<br/>
0 号 doge 跳跃到 2 号摩天楼，再跳跃到 4 号摩天楼（2 步）。<br/>
0 号 doge 将消息传递给 2 号 doge。<br/>
2 号 doge 跳跃到 3 号摩天楼,接着跳跃到 2 号摩天楼，再跳跃到 1 号摩天楼（3 步）。<br/>
2 号 doge 将消息传递给 1 号 doge。</span></div>

# Hint

<div class="content"><p></p><p> 子任务</p><br/>
<div>所有数据都保证 0≤Bi&lt;N。</div><br/>
<div></div><br/>
<div>子任务 1 （10 分）</div><br/>
<div>1≤N≤10</div><br/>
<div>1≤Pi≤10</div><br/>
<div>2≤M≤3</div><br/>
<div>子任务 2 （12 分）</div><br/>
<div>1≤N≤100</div><br/>
<div>1≤Pi≤100</div><br/>
<div>2≤M≤2000</div><br/>
<div>子任务 3 （14 分）</div><br/>
<div>1≤N≤2000</div><br/>
<div>1≤Pi≤2000</div><br/>
<div>2≤M≤2000</div><br/>
<div>子任务 4 （21 分）</div><br/>
<div>1≤N≤2000</div><br/>
<div>1≤Pi≤2000</div><br/>
<div>2≤M≤30000</div><br/>
<div>子任务 5 （43 分）</div><br/>
<div>1≤N≤30000</div><br/>
<div>1≤Pi≤30000</div><br/>
<div>2≤M≤30000</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

