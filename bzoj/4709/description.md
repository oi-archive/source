
# Description

<div class="content"><div>Flute 很喜欢柠檬。它准备了一串用树枝串起来的贝壳，打算用一种魔法把贝壳变成柠檬。贝壳一共有 N (1 ≤ N</div>
<div> ≤ 100,000) 只，按顺序串在树枝上。为了方便，我们从左到右给贝壳编号 1..N。每只贝壳的大小不一定相同，</div>
<div>贝壳 i 的大小为 si(1 ≤ si ≤10,000)。变柠檬的魔法要求，Flute 每次从树枝一端取下一小段连续的贝壳，并</div>
<div>选择一种贝壳的大小 s0。如果 这一小段贝壳中 大小为 s0 的贝壳有 t 只，那么魔法可以把这一小段贝壳变成 s</div>
<div>0t^2 只柠檬。Flute 可以取任意多次贝壳，直到树枝上的贝壳被全部取完。各个小段中，Flute 选择的贝壳大小 s</div>
<div>0 可以不同。而最终 Flute 得到的柠檬数，就是所有小段柠檬数的总和。Flute 想知道，它最多能用这一串贝壳</div>
<div>变出多少柠檬。请你帮忙解决这个问题。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第 1 行：一个整数，表示 N。</div>
<div>第 2 .. N + 1 行：每行一个整数，第 i + 1 行表示 si。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>仅一个整数，表示 Flute 最多能得到的柠檬数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2<br/>
2<br/>
5<br/>
2<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">21<br/>
//Flute 先从左端取下 4 只贝壳，它们的大小为 2, 2, 5, 2。选择 s0 = 2，那么这一段<br/>
里有 3 只大小为 s0 的贝壳，通过魔法可以得到 2×3^2 = 18 只柠檬。再从右端取下最后一<br/>
只贝壳，通过魔法可以得到 1×3^1 = 3 只柠檬。总共可以得到 18 + 3 = 21 只柠檬。没有<br/>
比这更优的方案了。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

