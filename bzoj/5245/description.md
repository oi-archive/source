
# Description

<div class="content"><div>对于正整数 n，定义欧拉函数 φ(n) 为小于等于 n 且与 n 互质的正整数个数。例如</div>
<div>φ(1) = 1， φ(8) = 4。</div>
<div>给定正整数序列 a1, a2, · · · , an，请依次执行 q 个操作，操作有以下三种类型：</div>
<div> 0 i x：修改 ai 的值为 x；</div>
<div> 1 l r：查询 φ(al + al+1 + · · · + ar) 的值，输出这个值对 10^9 + 7 取模的结果；</div>
<div> 2 l r：查询 φ(al × al+1 × · · · × ar) 的值，输出这个值对 10^9 + 7 取模的结果。</div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含两个正整数 n, q，分别表示序列长度及操作个数。</div>
<div>第二行包含 n 个正整数 a1, a2, · · · , an，表示初始序列。</div>
<div>接下来 q 行，每行三个整数 0 i x 或 1 l r 或 2 l r，表示一个操作。保证</div>
<div>1 ≤ i ≤ n， x ≥ 1， 1 ≤ l ≤ r ≤ n。</div>
<div>n ≤ 50000， q ≤ 100000，Ai及x&lt;=40000操作 0 的个数不超过 20000，所有的 ai、</div>
<div>操作 0 中的 i, x 及操作 1,2 中的 l, r 均在给定的限制下内均匀随机生成</div>
<p></p></div>

# Output

<div class="content"><div>对于每次形如 1 l r 或 2 l r 操作，输出一行，表示所求的值对 10^9 + 7 取模的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
1 3 5 7 9<br/>
1 2 4<br/>
0 3 3<br/>
1 1 4<br/>
2 1 4<br/>
0 3 4<br/>
2 1 3<br/>
0 4 5<br/>
1 3 5<br/>
1 1 5<br/>
2 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 <br/>
6<br/>
36<br/>
4 <br/>
6<br/>
10<br/>
144<br/>
【样例 1 解释】<br/>
初始序列为 1, 3, 5, 7, 9，依次进行的 10 个操作如下：<br/>
1. 查询 φ(3 + 5 + 7) = φ(15) = 8，输出 8；<br/>
2. 修改 a3 的值为 3，此时的序列为 1, 3, 3, 7, 9；<br/>
3. 查询 φ(1 + 3 + 3 + 7) = φ(14) = 6，输出 6；<br/>
4. 查询 φ(1 × 3 × 3 × 7) = φ(63) = 36，输出 36；<br/>
5. 修改 a3 的值为 4，此时的序列为 1, 3, 4, 7, 9；<br/>
6. 查询 φ(1 × 3 × 4) = φ(12) = 4，输出 4；<br/>
7. 修改 a4 的值为 5，此时的序列为 1, 3, 4, 5, 9；<br/>
8. 查询 φ(4 + 5 + 9) = φ(18) = 6，输出 6；<br/>
9. 查询 φ(1 + 3 + 4 + 5 + 9) = φ(22) = 10，输出 10；<br/>
10. 查询 φ(1 × 3 × 4 × 5 × 9) = φ(540) = 144，输出 144。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=作者未知，本站付费获得">作者未知，本站付费获得</a></p></div>

