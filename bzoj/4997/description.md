
# Description

<div class="content"><p> Why did the cow cross the road? Well, one reason is that Farmer John&#39;s farm simply has a lot of road</p>
<div>s, making it impossible for his cows to travel around without crossing many of them.</div>
<div></div>
<div>为什么牛过马路？ 其中一个简单的原因就是农民约翰的农场有很多道路，使得他的母牛不得不穿越许多道路。</div>
<div></div>
<div>FJ&#39;s farm is arranged as an N×N square grid of fields (2 &lt;= N &lt;= 100), Certain pairs of adjacent fi</div>
<div>elds (e.g., north-south or east-west) are separated by roads, and a tall fence runs around the exter</div>
<div>nal perimeter of the entire grid, preventing cows from leaving the farm. Cows can move freely from a</div>
<div>ny field to any other adjacent field (north, east, south, or west), although they prefer not to cros</div>
<div>s roads unless absolutely necessary.</div>
<div></div>
<div>FJ的农场在N×N的网格中（2≤N≤100），某些相邻的区域（例如，南北或东西）由道路分隔，高大的围栏围绕着</div>
<div>整个格栅的外围，防止牛离开农场。 牛可以从任何场地自由移动到任何其他相邻的区域（北，东，南或西），不</div>
<div>过除非不得已，她们并不愿意穿越道路。</div>
<div></div>
<div>There are K cows (1 &lt;= K &lt;= 100, K &lt;= N^2) on FJ&#39;s farm, each located in a different field. A pair o</div>
<div>f cows is said to be &#34;distant&#34; if, in order for one cow to visit the other, it is necessary to cross</div>
<div> at least one road. Please help FJ count the number of distant pairs of cows.</div>
<div></div>
<div>在FJ的农场有 K 头牛（1≤K≤100,K≤N^2)，每个位于不同的区域。 定义一对牛是“遥远的”，是指让一头牛访</div>
<div>问另一头牛时，必须至少穿过一条路。 请帮助FJ计算有多少对牛是“遥远的”。</div>
<div></div></div>

# Input

<div class="content"><p>The first line of input contains N, K, and R. </p>
<div>The next R lines describe R roads that exist between pairs of adjacent fields. </div>
<div>Each line is of the form r c c r&#39; c&#39;(integers in the range 1…N)</div>
<div>indicating a road between the field in (row r, column c) and the adjacent field in (row r&#39;,column c&#39;). </div>
<div>The final K lines indicate the locations of the K cows, each specified in terms of a row and column.</div>
<div></div>
<div>第一行输入包含 N， K和 R。</div>
<div>接下来的 R 行描述存在于相邻区域对之间的 R 条路。 每行的格式为 r, cc, r&#39;, c&#39; 都是在1...N中的整数）</div>
<div>表示在两个相邻的区域（第r行第c列，和第r行第c列）之间的路。 最终的K行表示 K 头牛的位置，也用行列来表示。</div>
<div></div></div>

# Output

<div class="content"><div>Print the number of pairs of cows that are distant.</div>
<div>输出遥远的牛数量对。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 3<br/>
2 2 2 3<br/>
3 3 3 2<br/>
3 3 2 3<br/>
3 3<br/>
2 2<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

