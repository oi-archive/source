
# Description

<div class="content"><p></p><dd>
<div>
<p>1tthinking 特别喜欢玩‘guitar hero’。 现在有 <em>N</em> (2 ≤ <em>N</em> ≤ 50) 首歌在这个游戏中，他们被标为 1 到 <em>N</em>。 游戏会随机把歌曲分组 <em>P</em>。 更详细的说, 对于 <em>P = &lt;P<sub>1</sub>, P<sub>2</sub>, ... P<sub>N</sub>&gt;</em>, 游戏会在第 <em>i</em> 首之后播放第 <em>P<sub>i</sub></em>首。 因此这 <em>N</em> 首歌会形成几个循环来播放. 举个例子, 如果 <em>N</em> = 3， <em>P</em> = &lt;2, 1, 3&gt; 我们得到了 {1, 2} 和 {3} 两个循环.</p>
<p>每首歌有一个积分值，1thinking特别喜欢玩Queen的 &#39;Another One Bites The Dust&#39;，每次他一定会玩这首歌。现在1thinking知道这首歌是积分值 <strong>第二大</strong> 的歌曲。他想知道他喜欢的歌所在的循环的分数和。 现在给出N首歌的难度值，求1tthinking游戏一次所获得的期望积分和是多少？</p>
<p>举个例子，当前有三首歌，积分为1、2、3。1tthinking总是会选择积分为2的歌曲。一共可能的排列有6种： &lt;1, 2, 3&gt;, &lt;1, 3, 2&gt;, &lt;2, 1, 3&gt;, &lt;2, 3, 1&gt;, &lt;3, 1, 2&gt; and &lt;3, 2, 1&gt;。 1tthinking分别会等概率选择 {2}, {2, 3}, {1, 2}, {1, 2, 3}, {1, 2, 3}, {2} 获得 2, 5, 3, 6, 6, 2 分。平均可以获得 (2 + 5 + 3 + 6 + 6 + 2) / 6 = 24 / 6 = 4.0000 分。</p>
<p><img src="/source/bzoj/2293/img/aHR0cDovL21lZGlhLm9wZW5qdWRnZS5jbi9pbWFnZXMvZzMyMDNfMS5qcGc=.jpg" alt=""/></p>
</div>
</dd>
<p></p></div>

# Input

<div class="content"><p></p><dt>  </dt>
<dd>
<div>
<p>第一个整数 <em>T</em>, 数据的组数。</p>
<p>对于每组数据，第一行，整数 <em>N</em>，表示排列的长度。</p>
<p>第二行，<em>N</em>个整数 <em>V<sub>1</sub></em>, <em>V<sub>2</sub></em>, ..., <em>V<sub>N</sub></em>, 每首歌的积分值。(0 ≤ <em>V<sub>i</sub></em> &lt; 2<sup>31</sup>)</p>
</div>
</dd>
<dt></dt>
<p></p></div>

# Output

<div class="content"><p>对于每组数据，一个浮点数，期望积分(精确到 0.000001)。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3<br/>
1 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
4.000000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

