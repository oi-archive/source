
# Description

<div class="content"><div>JOI 国将举行美术展，在美术展中将展出来自全国各地的各种美术品。现在有 N 件候选美术品，编号为 1 至 N。</div>
<div>每件艺术品有描述其尺寸与价值的两个整数，第 i 件艺术品的尺寸为 Ai，其价值为 Bi。美术展至少有一件美术</div>
<div>品被选中并展示，并且举办美术展的展览馆足够大，所以展出所有的 N 件美术品也是可行的。为了符合 JOI 国人</div>
<div>民的审美，我们想使得参展的美术品之间的尺寸之差不能太大。并且，我们想使得参展的美术品价值之和尽量大。</div>
<div>因此，我们决定按照以下方式选定参展的美术品：在参展美术品中，令 Amax 为所选美术品中最大的尺寸，Amin </div>
<div>为所选美术品中最小的尺寸。令 S 为所有参展美术品的总价值之和。我们想要最大化 S-(Amax-Amin)。</div>
<div>给出候选美术品的数量以及其尺寸与价值，你需要编写一个程序计算 S-(Amax-Amin) 的最大值。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包括一个整数 N，表示有 N 件候选美术品。</div>
<div>接下来 N 行，第 i+1 行给出两个整数 Ai, Bi，表示第 i 件美术品的尺寸与价值。</div>
<div>2≤N≤500000，1≤Ai≤10^15 (1≤i≤N)，1≤Bi≤10^9 (1≤i≤N)。</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示 S-(Amax-Amin) 的最大值。</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 <br/>
3 1<br/>
1 2 <br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
样例说明 1<br/>
在这个样例中，有三件候选美术品，其尺寸与价值分别为 2, 11, 4 与 3, 2, 5。<br/>
如果我们选择第一件美术品与第三件美术品参展，我们有 S-(Amax-Amin)=6。<br/>
在所有参选美术品中，Amax=4, Amin=2, S=3+5=8。可以证明 S-(Amax-Amin) 不超过 6。</span></div>

# Hint

<div class="content"><p></p><div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

