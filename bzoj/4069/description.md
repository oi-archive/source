
# Description

<div class="content"><div>印尼巴厘岛的公路上有许多的雕塑,我们来关注它的一条主干道。</div>
<div>在这条主干道上一共有 N 座雕塑，为方便起见，我们把这些雕塑从 1 到 N 连续地进行标号，其中第 i 座雕塑的年龄是 Yi 年。为了使这条路的环境更加优美，政府想把这些雕塑分成若干组，并通过在组与组之间种上一些树，来吸引更多的游客来巴厘岛。</div>
<div>下面是将雕塑分组的规则：</div>
<div>这些雕塑必须被分为恰好 X 组，其中 A&lt; = X&lt; = B，每组必须含有至少一个雕塑，每个雕塑也必须属于且只属于一个组。同一组中的所有雕塑必须位于这条路的连续一段上。</div>
<div>当雕塑被分好组后，对于每个组，我们首先计算出该组所有雕塑的年龄和。</div>
<div>计算所有年龄和按位取或的结果。我们这个值把称为这一分组的最终优美度。</div>
<div>请问政府能得到的最小的最终优美度是多少?</div>
<div>备注：将两个非负数 P 和 Q 按位取或是这样进行计算的：</div>
<div>首先把 P 和 Q 转换成二进制。</div>
<div>设 nP 是 P 的二进制位数，nQ 是 Q 的二进制位数，M 为 nP 和 nQ 中的最大值。P 的二进制表示为 pM−1pM−2…p1p0，Q 的二进制表示为 qM−1qM−2…q1q0，其中 pi 和 qi 分别是 P 和 Q 二进制表示下的第 i 位，第 M−1 位是数的最高位，第 0 位是数的最低位。</div>
<div>P 与 Q 按位取或后的结果是： (pM−1  OR  qM−1)(pM−2 OR qM−2)…(p1 OR q1)(p0 OR q0)。其中：</div>
<div>0 OR 0=0</div>
<div>0 OR 1=1</div>
<div>1 OR 0=1</div>
<div>1 OR 1=1</div>
<div></div>
<div></div></div>

# Input

<div class="content"><p>输入的第一行包含三个用空格分开的整数 N,A,B。</p>
<div></div>
<div>第二行包含 N 个用空格分开的整数 Y1,Y2,…,YN。</div>
<div></div></div>

# Output

<div class="content"><p>输出一行一个数，表示最小的最终优美度。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 1 3<br/>
8 1 2 1 5 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
<br/>
explanation<br/>
<br/>
将这些雕塑分为 2 组，(8,1,2) 和 (1,5,4)，它们的和是 (11) 和 (10)，最终优美度是 (11  OR  10)=11。（不难验证，这也是最终优美度的最小值。）</span></div>

# Hint

<div class="content"><p></p><p> 子任务 1 （9 分）</p><br/>
<div>1&lt; = N&lt; = 20</div><br/>
<div>1&lt; = A&lt; = B&lt; = N</div><br/>
<div>0&lt; = Yi&lt; = 1000000000</div><br/>
<div>子任务 2 （16 分）</div><br/>
<div>1&lt; = N&lt; = 50</div><br/>
<div>1&lt; = A&lt; = B&lt; = min{20,N}</div><br/>
<div>0&lt; = Yi&lt; = 10</div><br/>
<div>子任务 3 （21 分）</div><br/>
<div>1&lt; = N&lt; = 100</div><br/>
<div>A=1</div><br/>
<div>1&lt; = B&lt; = N</div><br/>
<div>0&lt; = Yi&lt; = 20</div><br/>
<div>子任务 4 （25 分）</div><br/>
<div>1&lt; = N&lt; = 100</div><br/>
<div>1&lt; = A&lt; = B&lt; = N</div><br/>
<div>0&lt; = Yi&lt; = 1000000000</div><br/>
<div>子任务 5 （29 分）</div><br/>
<div>1&lt; = N&lt; = 2000</div><br/>
<div>A=1</div><br/>
<div>1&lt; = B&lt; = N</div><br/>
<div>0&lt; = Yi&lt; = 1000000000</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

