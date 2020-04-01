
# Description

<div class="content"><p> 漆黑的晚上，九条可怜躺在床上辗转反侧。难以入眠的她想起了若干年前她的一次悲惨的OI 比赛经历。那是一道</p>
<div>基础的树状数组题。给出一个长度为 n 的数组 A，初始值都为 0，接下来进行 m 次操作，操作有两种：</div>
<div>1 x，表示将 Ax 变成 (Ax + 1) mod 2。</div>
<div>2 l r，表示询问 sigma(Ai) mod 2,L&lt;=i&lt;=r</div>
<div>尽管那个时候的可怜非常的 simple，但是她还是发现这题可以用树状数组做。当时非常young 的她写了如下的算</div>
<div>法：</div>
<div>1: function Add(x)</div>
<div>2: while x &gt; 0 do</div>
<div>3: A</div>
<div>x ← (Ax + 1) mod 2</div>
<div>4: x ← x ? lowbit(x)</div>
<div>5: end while</div>
<div>6: end function</div>
<div>7:</div>
<div>8: function Find(x)</div>
<div>9: if x == 0 then</div>
<div>10: return 0</div>
<div>11: end if</div>
<div>12: ans ← 0</div>
<div>13: while x ≤ n do</div>
<div>14: ans ← (ans + Ax) mod 2</div>
<div>15: x ← x + lowbit(x)</div>
<div>16: end while</div>
<div>17: return ans</div>
<div>18: end function</div>
<div>19:</div>
<div>20: function Query(l, r)</div>
<div>21: ansl ← Find(l ? 1)</div>
<div>22: ansr ← Find(r)</div>
<div>23: return (ansr ? ansl + 2) mod 2</div>
<div>24: end function</div>
<div></div>
<div>其中 lowbit(x) 表示数字 x 最?的非 0 二进制位，例如 lowbit(5) = 1, lowbit(12) = 4。进行第一类操作的时</div>
<div>候就调用 Add(x)，第二类操作的时候答案就是 Query(l, r)。如果你对树状数组比较熟悉，不难发现可怜把树状</div>
<div>数组写错了： Add和Find 中 x 变化的方向反了。因此这个程序在最终测试时华丽的爆 0 了。然而奇怪的是，在</div>
<div>当时，这个程序通过了出题人给出的大样例——这也是可怜没有进行对拍的原因。现在，可怜想要算一下，这个程</div>
<div>序回答对每一个询问的概率是多少，这样她就可以再次的感受到自己是一个多么非的人了。然而时间已经过去了很</div>
<div>多年，即使是可怜也没有办法完全回忆起当时的大样例。幸运的是，她回忆起了大部分内容，唯一遗忘的是每一次</div>
<div>第一类操作的 x的值，因此她假定这次操作的 x 是在 [li, ri] 范围内 等概率随机 的。具体来说，可怜给出了</div>
<div>一个长度为 n 的数组 A，初始为 0，接下来进行了 m 次操作：</div>
<div>1 l r，表示在区间 [l, r] 中等概率选取一个 x 并执行 Add(x)。</div>
<div>2 l r，表示询问执行 Query(l, r) 得到的结果是正确的概率是多少。</div>
<div></div></div>

# Input

<div class="content"><div>第一行输入两个整数 n, m。</div>
<div>接下来 m 行每行描述一个操作，格式如题目中所示。</div>
<div>N&lt;=10^5,m&lt;=10^5,1&lt;=L&lt;=R&lt;=N</div>
<div></div></div>

# Output

<div class="content"><div>对于每组询问，输出一个整数表示答案。如果答案化为最简分数后形如 x/y</div>
<div>
<div>，那么你只需要输出 x*y^?1 mod 998244353 后的值。（即输出答案模 998244353）。</div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 3 3<br/>
2 3 5<br/>
2 4 5<br/>
1 1 3<br/>
2 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
665496236<br/>
//在进行完 Add(3) 之后， A 数组变成了 [0, 1, 1, 0, 0]。所以前两次询问可怜的程序答案都是<br/>
1，因此第一次询问可怜一定正确，第二次询问可怜一定错误。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

